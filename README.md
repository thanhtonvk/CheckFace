Check full face object detection(onnx)
-	Resize size: 160*160
- BGR image
- Shape(160,160,3)
-	Label: 0: eyes , 1: skip(don’t care), 2: nose, 3: mouth
- ![image](https://user-images.githubusercontent.com/67794492/216495507-e676c4d5-ea71-44ca-9048-f7052cc49855.png)

=>check full face: 2 eyes, 1 nose, 1 mouth and next step

Check open and close eyes(tflite)
-	Crop 2 eyes
- BGR image
-	Resize 96*96
-	Normalize image 0-1
- Shape(96*96*3)
- Label:	0: close 1: open
=>Check all eyes open with proba > 0.7 passed


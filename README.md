Check full face object detection
-	Resize size: 160*160
-	Label: 0: eyes , 1: skip(don’t care), 2: nose, 3: mouth
- ![image](https://user-images.githubusercontent.com/67794492/216495507-e676c4d5-ea71-44ca-9048-f7052cc49855.png)

=>check full face: 2 eyes, 1 nose, 1 mouth and next step
Check open and close eyes
-	Crop 2 eyes
-	Resize 96*96
-	Scale 0-1(image/=255.0)
- Label:	0: close 1: open
=>Check all eyes open with proba > 0.7 passed


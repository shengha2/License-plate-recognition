# License-plate-recognition
LPR exe works on Ontario license plate 
The instruction is as following:
1. Relocate “model” folder under driver C root directory
2. Run ICE_VLPR_VDC.exe, software support patch images, single image and video stream recognition. 
3. Edited “LP Min. pixelWidth” “LP Max. pixelWidth” and “confidence threshold” will be active after patch or single image recognition.

The recognition modes:
1. Batch Rec: need to set the “Read Dir” to corresponding image directory and “Save Dir” for results saving directory.
2. Single Rec:  select corresponding image.
3. Video Rec: select corresponding video file, video will display on screen, OSD will superimposed, use mouse draw recognition area on the screen,  press the "s" to start processing, recognition automatically 

  
Notice：
1. Best recognition result attend when LP PixelWidth around 120 px, might come no result if far beyond it.
2. LP PixelWidth has to be multiple of 4
3.Please install “plug in” if software failed to active.

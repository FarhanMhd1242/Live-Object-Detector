# Live-Object-Detector
* This object detector is based on You only look once (YOLO) is a state-of-the-art, real-time object detection system.
* it processes images at 30 FPS and has a mAP of 57.9% on COCO dataset.
* This system is implemented by using YOLOv3.
* It can detect over 80 different types of objects.
  * person
  * bicycle
  * car
  * motorbike
  * aeroplane
  * bus
  * train
  * truck
  * boat
  * traffic light 
  * cat
  * dog
  * tvmonitor
  * laptop
  * mouse
  * cell phone and so on..

**Applications and Scope:** We can further train this model on any custom data 
* for example : 
  * face detection
  * Number plate detection
  * skin disease detection
  * Polyp detection in Colonoscopy images or anything which you want..

**Instruction to run the code**
* first download the yolov3.weights from the link : https://pjreddie.com/media/files/yolov3.weights  
* open the Live-object-detector.ipynb in jupyter Notebook.
* before running this install all the dependent libraries openCV, numpy, etc..
* put together all the files in same folder where Live-object-detector.ipynb is stored and run the code
  * coco.names
  * yolov3.cfg
  * yolov3.weights                     

# YOLO using OpenCV and Python 

OpenCV `dnn` module supports running inference on deep learning models. 
 
 ## Dependencies
  * opencv
  * numpy
  
 ## YOLO (You Only Look Once)
 
 Download the YOLO v3 weights file from the following links and place it in the current directory.
 
 yolov3-tiny.weights (train by ourself)
 https://drive.google.com/open?id=1r2n0R3iuXmhuwwOGgM0tamRlu_Uz4rWL
 
 yolov3-tiny.cfg (used for train)
 https://drive.google.com/open?id=1-5oTRBSdhfrmJCvnsj274HLL804pykSq
 
 name.txt (used for train)
 https://drive.google.com/open?id=1FbmSyPMGsTHm_u38ndWyWHp6iuBUmRHu
 
 `$ python yolo_opencv.py --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt --image car.jpg --video 333.mp4`
 
 **Command format** 
 
 _$ python yolo_opencv.py --config /path/to/config/file --weights /path/to/weights/file --classes /path/to/classes/file --image /path/to/input/image --video /path/to/input/video_ 

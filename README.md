# YOLOv3
Implementation of YOLOv3 using opencv and python
### author: devShyam

## Dependencies:
  Opencv ver 3 or above
  
  - imutils

  - numpy

  - scikit-learn

  - matplot-lib

## file structure:
parent: YOLO

### sub directories:
 -  images    
     
  - videos (Contains input images and videos respectively)

  - output(to store output)
     
  - yolo-coco (Conatins weights and cfg files)
     
  - yolo.py 
     
  - yolo_videos.py

## Instructions:
#### yolo.py is a single image processing yolo implementation.

command to invoke it  : "python yolo.py --image images/imagename.jpg --yolo folder_containing_weights_and_cfg

#### yolo_video.py is video processing yolo implementation  

command to invoke it : "python yolo_video.py --input inputpath.avi --output outputpath.avi --yolo  folder_containing_weights_and_cfg



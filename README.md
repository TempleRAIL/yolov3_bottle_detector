# Yolov3 Bottle Detector
![bottle_detection_demo](demo/bottle_detection_demo.gif "bottle_detection_demo") 

## Custom Bottle Dataset:
This bottle dataset consists of 4870 images of four brands of mineral water bottles (i.e. Aquafina, Deer, Kirkland and Nestle). Images were collected by the turtlebot 2 robot and people in four different environments: lobby, laboratory, corridor, and living room. 

**Size** 
* 4000 training images
* 870 validation images

**Bottle Classes**
* Aquafina
* Deer
* Kirkland
* Nestle

**Format**
* PASCAL VOC
* Darknet

**Download link**
* https: 

**Dataset Folder Structure**
* Annotations: contains the xml label files in PASCAL VOC format
* ImageSets: contains the training index files 
* JPEGImages: contains the image data in jpg format
* Labels: contains the txt lable files in Darknet format

**Sample labeled Images**
![pv_corridor](demo/pv_corridor.jpg "pv_corridor") ![lobby](demo/lobby.png "lobby") ![lab126](demo/lab126.jpg "lab126") 

## YOLOV3 Tiny Bottle Detector:
This bottle detector is a pretrained yolov3-tiny model fine-tuned by our custom bottle dataset shown above. 

**Two pretrained models**
* yolov3_tiny_sphd_25000_paper.weights: specially used in our SPHD filer paper "The Semantic PHD Filter for Multi-class TargetTracking: From Theory to Practice"
* yolov3_tiny_30000_general.weights: general purpose

**Requirements**
* install darknet package: https://github.com/pjreddie/darknet  

## Citation




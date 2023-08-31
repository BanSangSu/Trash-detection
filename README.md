# Trash-detection
**Using Yolov5 model with TACO dataset**
- **Period**: 13th - 14th Nov, 2021

# AI Recycling Garbage Detection System for Recycling Companies

https://github.com/BanSangSu/Trash-detection/assets/76412884/e64ce631-bd66-4797-8426-d1ff9bca0bfc)](https://github.com/BanSangSu/Trash-detection/assets/76412884/e64ce631-bd66-4797-8426-d1ff9bca0bfc

# Outline
1. A system that detects only reusable waste at a recycling facility.



# Tech Stacks
- **Pytorch, YOLOv5**

# Benefit
1. Save money on discarded waste.
2. Reduce the maintenance costs used by recyclers.

# Functions
1. Our model receives a video or image and shows results through a model trained on the data (TACO).

# TroubleShooting
1. Overfitting occurred.  
  ->> (Todo) I need to do more mork to reduce overfitting.  
2. Due to YOLOv5's characteristic of seeing objects as independent objects in each frame, the accuracy was greatly dropped.  
  ->> (Todo) I would like to use other models(Semantic Segmentation, Instance Segmentation models)

# Futher
1. I'd like to build a robotic arm and operate it together.

# How to use
1. You have to change the number of categories in the **data folder** or **models folders**, and set the path in yaml again according to the data you want to use. Also, you should make good use of **prepareDataset**, which converts coco format data to object detection format according to this code based on YOLO.

# Road Damage Detection using YOLOv5

## Project Overview
This project implements an automated road damage detection system using deep learning and computer vision techniques. Leveraging the YOLOv5 object detection model, the system identifies and classifies common road surface defects such as potholes and various types of cracks from images captured via crowd-sourced or instrumented vehicle datasets.

The model is trained on a publicly available, YOLO-formatted road damage dataset and optimized for high accuracy and real-time inference capability. This solution is applicable to smart city infrastructure monitoring, road maintenance planning, and traffic safety enhancement.

## Features
- Detection and classification of multiple road damage types:
  - Alligator cracking
  - Lateral cracking
  - Longitudinal cracking
  - Potholes
- Uses YOLOv5 architecture for fast and accurate object detection
- Training pipeline implemented in Python with PyTorch and OpenCV
- Supports GPU acceleration and runs efficiently on Google Colab
- Includes visualization of detection results on test images

## Dataset
The model is trained on the [Road Damage Detection YOLO v11](https://www.kaggle.com/datasets/rogersinghchugh/road-damage-detection-yolo-v-11) dataset from Kaggle, which contains labeled images of road damages with bounding box annotations formatted for YOLO.

## Results
- High precision detection of multiple road damage types  
- mAP and confidence thresholds optimized for real-world application  
- Visualized bounding boxes for intuitive result interpretation  

## Future Work
- Real-time video stream processing for on-the-fly road condition monitoring  
- Deployment on edge devices like NVIDIA Jetson Nano for in-vehicle use  
- Integration with GIS systems for spatial mapping of road damage  

## References
- [YOLOv5 Repository](https://github.com/ultralytics/yolov5)  
- [Road Damage Detection Dataset (Kaggle)](https://www.kaggle.com/datasets/rogersinghchugh/road-damage-detection-yolo-v-11)

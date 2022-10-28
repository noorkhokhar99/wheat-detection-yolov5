# Wheat Detection
Detecting wheat heads using YOLOv5
- [Web App demo](#Web-app-demo)
- [Brief overview of the competition images](#Brief-overview-of-the-competition-images)
- [Modifications](#Modifications)
- [Inference and Deployment](#Inference-and-Deployment)




## Pre-trained models
Models can be downloaded from <a href="https://www.kaggle.com/ii5m0k3ii/mixup50e">here</a>. (Use last_yolov5x_4M50fold0.pt for best results) 


### Steps to run Code
- Clone the repository.
```
git clone https://github.com/noorkhokhar99/wheat-detection-yolov5.git
```
- Goto the cloned folder.
```
cd wheat-detection-yolov5

```
- Upgrade pip with mentioned command below.
```
pip install --upgrade pip
```
- Install requirements with mentioned command below.
```
pip install -r requirements.txt
```
- Download [models](https://www.kaggle.com/ii5m0k3ii/mixup50e) object detection weights from link and move them to the working directory {models-Wheat-Detection}
- Run the code with mentioned command below.
```
#if you want to change source file
python detect_and_blur.py --weights yolov7.pt --source "your video.mp4" --blurratio 20

```

### Results


<img src="https://github.com/noorkhokhar99/yolov7-object-blurring/blob/main/Screen%20Shot%201444-03-28%20at%2011.00.34%20AM.png">


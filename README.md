# ObjectDetection-ComputerVision
This repo contains all the notebooks dedicated to object detection and computer vision. 

# NOTEBOOK 1

# ResNet_ClassifierRegressor  - Custom Object Detection Model from Scratch using ResNet34
It is a pytorch notebook that detects the indian currencies of Rs. 10, 20, 50, 100, 200 , 500 and 2000 and creates a bounding box around them. I have used ResNet34 model and trained it with images along with their annotations xml file and their class names. 

Currency_Dataset Folder - contains 414 images and annotations file of Indian currencies. I have manually collected them from the internet and created bounding box around them using labelImg annotation tool.

Result - model is not that perfect because 400 images are very less. But it will give you an idea how to make such model from scratch if you don't want to use YOLO or TensorFlow Object Detection API. Dataset with more than 10,000 images will do the work I guess.


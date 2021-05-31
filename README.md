 # Custom Object Detection Model from Scratch using ResNet34 and Xception 
 
It is a pytorch notebook that detects the indian currencies of Rs. 10, 20, 50, 100, 200 , 500 and 2000 and creates a bounding box around them. I have used ResNet34 model and trained it with images along with their annotations xml file and their class names. 

500 Rs Image

![500 rs](https://github.com/epicure24/ObjectDetection-ComputerVision/blob/main/Currency_Dataset/images/fiveHundred/500_1%20(copy).jpeg)

Annotation xml 

		<bndbox>
			<xmin>15</xmin>
			<ymin>28</ymin>
			<xmax>312</xmax>
			<ymax>125</ymax>
		</bndbox>
		
Image with Bounding Box

![bb](https://github.com/epicure24/ObjectDetection-ComputerVision/blob/main/Currency_Dataset/index.png)

Currency_Dataset Folder - contains 414 images and annotations file of Indian currencies. I have manually collected them from the internet and created bounding box around them using labelImg annotation tool.

Result - model is not that perfect because 400 images are very less. But it will give you an idea how to make such model from scratch if you don't want to use YOLO or TensorFlow Object Detection API. Dataset with more than 10,000 images will do the work I guess.

## ANNOTATION

I have manually annotated the images using **labelImg** annotation tool.

## STEPS TO DOWNLOAD on Ubuntu

sudo apt-get install pyqt5-dev-tools

sudo pip install lxml

Now clone the [labelImg GitHub repository](https://github.com/tzutalin/labelImg) on your machine or download the zip file here and extract.

cd into the labelImg directory cd labelImg-master

In your terminal type make qt5py3

That’s it. Now you can Run the python labelImg.py to run the labelImg.

For other OS, [refer to this article](https://mlnotesblog.wordpress.com/2017/12/16/how-to-install-labelimg-in-ubuntu-16-04/)

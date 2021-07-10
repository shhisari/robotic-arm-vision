# robotic-arm-vision

Object Detection using YOLO v3 trained on MS COCO dataset.

Simple demo on how to use darknet implementation of YOLO v3 for object detection.

To run, create a working directory

Clone the darknet code and download weights
```
cd object_detection
git clone https://github.com/pjreddie/darknet
wget https://pjreddie.com/media/files/yolov3.weights -P weights/
```


INPUT IMAGE

![test3](https://user-images.githubusercontent.com/8944710/125175148-10ea4800-e198-11eb-99b2-f7c3a86c6180.jpeg)


Run the detect.py file to print the image and the bounding boxes as below
```
python3 detect.py test_img.jpg
```
OUTPUT IMAGE

<img width="632" alt="Screenshot 2021-06-17 at 12 38 15 PM" src="https://user-images.githubusercontent.com/8944710/125175153-25c6db80-e198-11eb-9161-1dce6b7bb7e9.png">



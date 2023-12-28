# Pothole detection using YoLoV4

## PREREQUISITES: 

1. Python
2. Dependencies like CUDA, OpenCV and Tensor Flow.

## OVERVIEW:

Detection of potholes using live webcam and a flask application: 
![image](https://user-images.githubusercontent.com/66819327/128059812-b86fc94c-3ed6-4d35-ac37-4d5074c240fd.png)
Sorry for the bad clarity!!

## DATASET:

There are about 10,000 live images which were manually annotated and labelled. Out of which 6000 are for training and 4000 for testing. This project works with Yolov4 that has darknet as the main source. Resize all the images as the same size. 

## TRANING AND TESTING:

Training on such a large dataset will take hours or sometimes even days, so lets divide them into sub batches and for evaluation lets use MAP. As a part of the next step, a live web camera detection of camera is trained and its later converted to tensorflow wights to feed it into the flask application. 

## YOLOV4:

Only one model is used here thats YoLoV4

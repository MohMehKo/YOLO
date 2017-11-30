# YOLO
Autonomous driving - Car detection
<<<<<<< HEAD
<<<<<<< HEAD

## Object detection using  YOLO model.
 Many of the ideas in this notebook are described in the two YOLO papers: Redmon et al., 2016 (https://arxiv.org/abs/1506.02640) and Redmon and Farhadi, 2016 (https://arxiv.org/abs/1612.08242).

## How to
1- Use object detection on a car detection dataset

2- Deal with bounding boxes

## Problem
Problem Statement
You are working on a self-driving car. As a critical component of this project, you'd like to first build a car detection system. To collect data, you've mounted a camera to the hood (meaning the front) of the car, which takes pictures of the road ahead every few seconds while you drive around.
You've gathered all these images into a folder and have labelled them by drawing bounding boxes around every car you found. Here's an example of what your bounding boxes look like.
If you have 80 classes that you want YOLO to recognize, you can represent the class label  c
  either as an integer from 1 to 80, or as an 80-dimensional vector (with 80 numbers) one component of which is 1 and the rest of which are 0.
  
Model details

First things to know:
- The **input** is a batch of images of shape (m, 608, 608, 3)
- The **output** is a list of bounding boxes along with the recognized classes. Each bounding box is represented by 6 numbers $(p_c, b_x, b_y, b_h, b_w, c)$ as explained above. If you expand $c$ into an 80-dimensional vector, each bounding box is then represented by 85 numbers. 
=======
>>>>>>> aa08a62d867ab44d92341a8cf9226ae74377994b
=======
>>>>>>> aa08a62d867ab44d92341a8cf9226ae74377994b

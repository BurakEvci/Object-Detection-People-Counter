# People Detection and Counting System

This project is a computer vision application that detects, tracks, and counts people crossing defined boundary lines in a video feed. The main components and workflow of the project are as follows:

![image](https://github.com/user-attachments/assets/5d7ac9fa-1e83-4ce6-a075-6582f1e98ee3)


## 1. Video Processing with OpenCV
The project reads frames from a video file (people.mp4).

The frames are combined with a mask (mask.png) to enhance detection.
## 2. Object Detection with YOLO Model
The YOLOv8 model is used to detect objects such as people.

Detected objects are labeled with their class names and confidence scores.
## 3. Object Tracking with SORT Algorithm
The Sort algorithm tracks detected objects and assigns a unique ID to each one.

The positions of the objects are updated in each frame.
## 4. Boundary Lines and Counting Mechanism
Two boundary lines (limitsUp and limitsDown) are defined on the image.

Objects crossing these lines are counted, and each crossing event is recorded separately for upward and downward directions.
## 5. Drawing and Displaying Information on the Image
The system detects whether the objects have crossed the boundary lines; when crossed, the line changes color to green.

Each tracked object's ID and the count information are displayed on the image.
## Use Case
This project simulates a people tracking and counting system that can be used in scenarios such as crowd monitoring, security applications, and data analysis.

Note: I do not own the copyrights of this project.(youtube @murtazasworkshop) It is for learning purposes only.

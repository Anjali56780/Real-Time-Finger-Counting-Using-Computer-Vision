# Real-Time-Finger-Counting-Using-Computer-Vision
The system successfully detects and segments a user's hand from the video stream and estimates the number of fingers being shown, enabling basic gesture recognition in real time.
This project focuses on developing a real-time hand gesture recognition system using OpenCV and Python. The system captures live video through a webcam and processes the video frames to detect and track hand movements. A Region of Interest (ROI) is defined where the user's hand is placed, and background subtraction techniques are used to separate the hand from the surrounding environment.

The project utilizes image processing techniques such as grayscale conversion, Gaussian blurring, thresholding, contour detection, and convex hull analysis to identify the shape of the hand. By analyzing the contour of the segmented hand and calculating convex features, the system is able to count the number of fingers displayed by the user in real time.

The primary objective of the project is to demonstrate how computer vision can be used for gesture-based human-computer interaction without requiring specialized hardware. Such systems can be applied in touchless interfaces, gaming, virtual control systems, sign language recognition, robotics, and smart automation applications.

Key Features:

Real-time video capture using a webcam.
Background modeling and subtraction for hand segmentation.
Hand contour extraction and convex hull computation.
Finger counting through geometric analysis.
Interactive visual feedback displayed on the screen.

Technologies Used:

Python
OpenCV
NumPy
Scikit-learn (pairwise distance calculations)

Outcome:
The system successfully detects and segments a user's hand from the video stream and estimates the number of fingers being shown, enabling basic gesture recognition in real time.

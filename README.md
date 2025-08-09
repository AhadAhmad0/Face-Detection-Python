# Face-Detection-Python

This project is a simple yet effective face detection application built with Python’s OpenCV library. It uses the Haar Cascade Classifier (haarcascade_frontalface_default.xml) to detect human faces in images and live webcam. Haar cascades are fast, lightweight, and work well for real-time detection in many scenarios.

# Features:
1.Detects the face in a single frame.

2.Works with images and webcam streams.

3.Lightweight and easy to run on most systems.

4.Uses pre-trained Haar cascade model provided by OpenCV.

# How It Works:
1.Haar Cascade Classifier – A machine learning object detection algorithm that identifies objects in images based on positive and negative training examples.

2.The program loads the haarcascade_frontalface_default.xml file, which contains the trained data for frontal face detection.

3.The input (image and webcam frame) is converted to grayscale to simplify computation.

4.The classifier scans the image at multiple scales to locate faces.

5.Detected faces are highlighted with rectangles.

I have also provided the Haar cascade frontalface file.

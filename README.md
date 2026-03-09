## Face-Detection

# Overview
This project is a real-time face detection application built using Python, OpenCV, and PySimpleGUI. The program uses a computer’s webcam to detect human faces in real time and highlights them with bounding boxes while also displaying the number of faces currently visible on the screen.

The graphical interface allows the user to easily view the video feed and detection results without needing to interact directly with the command line during execution.

# Purpose
The purpose of this project was to explore computer vision concepts and understand how machine learning models can detect objects—in this case, human faces—from live video input.

Face detection is widely used in many real-world applications, including:
- Smartphone face unlock systems
- Security cameras
- Attendance tracking systems
- Video conferencing software

This project helped demonstrate how these systems work at a basic level by using OpenCV’s pretrained Haar Cascade face detection model.

# How it works
1. The program accesses the computer’s webcam using OpenCV.
2. Each frame of the video feed is converted into grayscale to improve detection performance.
3. The program applies a Haar Cascade classifier trained to detect human faces.
4. When faces are detected:
   - Green rectangles are drawn around each detected face.
   - The number of detected faces is displayed in the window.
5. The video feed is displayed in a PySimpleGUI window.

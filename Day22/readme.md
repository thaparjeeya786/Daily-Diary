# Artificial Intelligence & Machine Learning Training Report - Day 22
**Name:** Jeeya Thapar  
**URN:** 2303002  
**Date:** 22 July 2025  

## Overview
Today I implemented a **real-time face recognition system** using Python. Unlike face detection, which only finds where a face is, face recognition identifies *who* the person is by comparing live faces with stored known images. The project focused on building an **automatic attendance system** using a webcam, where recognized individuals are marked as "Present" in a CSV file. I used the **face_recognition** and **OpenCV** libraries to handle both facial processing and visual output.

## Learning Objectives
- Understand how face recognition differs from face detection.  
- Learn to encode known faces using the `face_recognition` library.  
- Perform real-time face matching with a webcam feed.  
- Automate attendance tracking and save it to a CSV file.  


## Main Concepts
Face recognition goes beyond just detecting faces; it helps identify who the person is.  
Using the `face_recognition` library, I was able to:  
- Encode known faces (students or employees).  
- Compare live faces from the webcam.  
- Draw bounding boxes and labels on recognized faces.  
- Save their names and timestamps in an attendance file.  


## Code Features
1. Loaded images of known people and generated face encodings.  
2. Opened the webcam and captured frames in real time.  
3. Resized and converted frames to RGB for processing.  
4. Detected faces in each frame and generated their encodings.  
5. Compared each detected face with known encodings using:  
   - `compare_faces()` → to check if a match exists.  
   - `face_distance()` → to measure closeness (smaller distance = better match).  
6. If a match was found:  
   - Displayed the person’s name on the webcam.  
   - Drew a green rectangle around the face.  
   - Marked attendance by writing name + time into a CSV file.  
7. If no match was found:  
   - Displayed "Unknown".  
   - Drew a red rectangle around the face.  

## Key Highlights
- Built a real-time face recognition-based attendance system in Python.  
- Used `face_recognition` to encode and compare faces.  
- Used OpenCV for webcam access and visualization.  
- Understood face encodings, comparison, and distance metrics.  
- Practiced file handling with CSV for attendance logging.  
- Improved efficiency by resizing frames before processing.  


## Conclusion
Today's day was highly practical and productive. I successfully created a working **face recognition attendance system** that detected both known and unknown faces in real time. Using the `face_recognition` library made encoding and matching straightforward, while OpenCV handled camera access and visualization. Attendance was logged automatically in a CSV file with timestamps. This session strengthened my confidence in building **real-world AI applications** and gave me hands-on experience with computer vision and machine learning libraries in Python.


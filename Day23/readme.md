# Artificial Intelligence & Machine Learning Training Report - Day 23
**Name:** Jeeya Thapar  
**URN:** 2303002  
**Date:** 23 July 2025  

## Overview
On the final day of training, I successfully developed and tested a **complete real-time face recognition-based attendance system**. The system uses a webcam to capture live video, detects and recognizes faces by comparing them with stored encodings, and logs attendance into a CSV file with timestamps. It was built entirely in **Python** using the **face_recognition**, **OpenCV**, and **pandas** libraries, focusing on deep-learning-based encodings instead of Haar cascades.

## Learning Objectives
- Compare live facial input with stored encodings for recognition.  
- Implement real-time face recognition using face_recognition and OpenCV.  
- Automate attendance logging with **pandas** and CSV handling.  
- Distinguish between **known and unknown faces** and label them accordingly.  
- Integrate all components into a fully functional end-to-end project.  

## What I Implemented
### 1. Face Encoding Setup
- Loaded and encoded images from a dataset folder using face_recognition.  
- Stored encodings along with associated names for comparison.  

### 2. Attendance Logging
- Used pandas to manage an attendance.csv file.  
- Logged the person’s name and timestamp only if they weren’t already marked present.  

### 3. Live Recognition with OpenCV
- Captured video from webcam with cv2.VideoCapture(0).  
- Detected and encoded faces in each frame.  
- Compared them with known encodings using:  
  - compare_faces() → checked for matches.  
  - face_distance() → found the closest known match.  
- Drew bounding boxes:  
  - Green for recognized faces (with name label).  
  - Red for unknown faces.  

### 4. Handling Unknown Faces
- Unrecognized faces were labeled “Unknown”.  
- Program continued smoothly without interruption.  

## Real-Time Face Recognition Workflow
1. Webcam captures frames.  
2. Faces are detected and encoded using face_recognition.  
3. Encodings are compared with the known dataset.  
4. Recognized individuals are labeled, displayed, and logged in attendance.csv with a timestamp.  
5. Unknown individuals are highlighted but not logged.  

## Conclusion
Today it  marked the successful completion of my face recognition project. I built a fully working system that can:  
- Recognize multiple known faces in real time.  
- Log attendance automatically and accurately.  
- Handle unknown faces safely without errors.  
- Provide an intuitive interface with bounding boxes and labels.  

This final project brought together everything I learned in the training. It gave me **hands-on experience in AI/ML, computer vision, and real-world integration**. I now feel confident about applying these skills to practical applications like **smart attendance systems, surveillance, and personalized recognition systems**.



# Artificial Intelligence & Machine Learning Training Report - Day 21
**Name:** Jeeya Thapar  
**URN:** 2303002  
**Date:** 21 July 2025  

## Overview
Today’s session marked the **beginning of my hands-on AI project on Face Recognition**. I explored how face recognition systems work in real life, such as biometric attendance, device unlocks, and surveillance. The session introduced the workflow — capturing an image, detecting faces, extracting features, and comparing those features for identification. I also learned about the libraries, dataset planning, and installations required for the project.

## Learning Objectives
- Understand the concept and purpose of a Face Recognition system.  
- Explore real-life applications and importance in today’s digital world.  
- Learn about Python libraries used in face recognition (**OpenCV, face_recognition, NumPy**).  
- Set up the project environment in **Visual Studio Code**.  
- Install dependencies and configure camera access.  
- Learn best practices for folder structure and dataset organization.  

## Project Setup
I started by creating a virtual environment and installing the required libraries:  

```bash
python -m venv myenv
.\myenv\Scripts\activate
pip install opencv-python face_recognition numpy
```
After setup, I verified camera access and organized folders for dataset, encodings, and outputs.
A sample Python script was written to check webcam functionality:
```bash
import cv2  
cap = cv2.VideoCapture(0)  
while True:  
    ret, frame = cap.read()  
    cv2.imshow('Webcam Test', frame)  
    if cv2.waitKey(1) & 0xFF == ord('q'):  
        break  
cap.release()  
cv2.destroyAllWindows()
```


### Tools & Libraries Used
- Python 3.10
- OpenCV – For image capture and face detection.
- face_recognition – For encoding and comparing faces.
- NumPy – For handling numerical data.
- Visual Studio Code – IDE for development.
- Virtual Environment – To isolate dependencies.
- Other Tools: pip, GitHub

## Key Highlights
- Learned the difference between Face Detection (finding a face in an image) and Face Recognition (identifying whose face it is).
- Successfully set up a virtual environment and installed required dependencies.
- Verified system readiness by running a webcam test script.
- Organized project folders for smooth workflow and dataset management.

## Conclusion
Today I  laid the foundation for my face recognition project. By preparing the development environment and verifying installations, I am now ready to move into dataset collection and face encoding. This session was exciting as it bridged theory with real-world applications, showing how machine learning and computer vision come together to build practical AI systems.

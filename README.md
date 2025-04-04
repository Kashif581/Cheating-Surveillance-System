# Cheating-Surveillance-System


## Overview 
**The Cheating Surveillance System** is designed to detect cheating during Online Interviews/Exams by monitoring head and pupil movements and identifying unauthorized mobile phone usage. This system integrates facial landmark detection with Shape Predictor 68 and object detection using YOLO, trained on a cellphone detection dataset from Roboflow.

## Features
* **Head and Pupil Movement Detection:** Dlib's Shape Predictor 68 is used to track facial landmarks and detect suspicious gaze patterns.
* **Mobile Phone Detection:** This method utilizes a **YOLOv12** model trained on the [Roboflow Cellphone Detection Dataset](https://universe.roboflow.com/d1156414/cellphone-0aodn) to detect mobile phones in real-time.
* **Real-Time Monitoring:** Processes live video feeds for instant analysis and detection.
* **Alert System:** Detects and flags potential cheating behavior, such as excessive head or pupil movement in the left, right, up, or down direction for longer than the allowed time.

## Technologies Used
* Python
* OpenCV (for video processing)
* dlib (for facial landmark detection)
* YOLO (You Only Look Once) (for object detection)
* Roboflow Dataset (for training the mobile detection model)


https://github.com/user-attachments/assets/a24be595-f4b0-4be6-8a89-cec3b81ff4d0


https://github.com/user-attachments/assets/37e2fa97-51e8-4a20-852b-78d0fa587310






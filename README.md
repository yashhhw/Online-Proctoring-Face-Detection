# Online Proctoring Face Detection

## Overview
This project is a real-time face detection system built for online proctoring purposes. It ensures that only one face appears on the screen during an exam to maintain the integrity of the examination process. The system captures live video from the webcam, detects faces, and displays the number of faces on the screen in real-time.

## Features
- **Real-time face detection**: Utilizes OpenCV's DNN-based models for accurate face detection.
- **Face counting**: Continuously checks the number of faces on the screen and displays the count.
- **Face bounding boxes**: Draws bounding boxes around detected faces.
- **Proctoring enforcement**: The system alerts if more than one face is detected, indicating potential cheating.

## Technologies Used
- Python
- OpenCV
- Deep Learning Models 

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Online-Proctoring-Face-Detection.git

##Future Enhancements
1. Integrate with online exam platforms.
2. Add support for face recognition to verify the identity of the exam taker.

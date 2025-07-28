# Face-Detection-Alarm-System
A Python Jupyter Notebook for real-time face detection with audio alerts using OpenCV, gTTS, and playsound.
# Face Detection and Alarm System

A Python Jupyter Notebook for real-time face detection with audio alerts using OpenCV, gTTS, and playsound.

## Description
This Jupyter Notebook uses OpenCV's Haar Cascade classifier to detect faces via a webcam, drawing rectangles around detected faces. It triggers audio alerts using `gTTS` and `playsound` (or `pygame` for cross-platform support) when faces are detected or no longer detected. The system generates a temporary `fire_alarm.mp3` file for audio output, which is deleted after use.

## Prerequisites
- Python 3.11 or later
- A webcam
- Audio drivers configured (for `playsound` or `pygame`)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/FaceDetectionAlarmSystem.git
   cd FaceDetectionAlarmSystem

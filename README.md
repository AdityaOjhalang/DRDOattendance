# DRDO Attendance System with Face Recognition 📸

Welcome to the DRDO Attendance System! This project is designed to automate the attendance process using the power of face recognition. Built with Python, this system leverages the face_recognition library and PyQt5 for a seamless GUI experience.

## 🌐 Overview

The system captures real-time video feed from the default camera (typically a webcam), detects faces, and recognizes them against a predefined set of known faces. Once a face is recognized, the attendance is marked with a timestamp.

### 🌟 Features

1. **Real-time Face Recognition**: Recognize faces in real-time with the face_recognition library.
2. **Interactive GUI**: A user-friendly GUI built using PyQt5.
3. **Attendance Logging**: Recognized faces have their attendance marked with the current timestamp.

## 🛠️ How It Works

### 1. **Face Detection & Recognition**:
- The system captures video frames and detects faces in each frame.
- Each detected face is encoded and compared against known face encodings.
- If there's a match, the system recognizes the face and logs the attendance.

### 2. **GUI Interaction**:
- The main window (`mainwindow.py`) provides an interface for the user to initiate the face recognition process.
- Upon starting, the output window (`out_window.py`) displays the video feed with real-time face recognition. Recognized faces are highlighted with their names.

### 3. **Attendance Logging**:
- When a face is recognized, the attendance is logged in an 'Attendance.csv' file with a timestamp.

## 🚀 Getting Started

1. **Setup**:
   - Clone the repository.
   - Install the required Python libraries: PyQt5 and face_recognition.

2. **Run**:
   - Execute the `mainwindow.py` script to launch the GUI.
   - Click the "Run" button to initiate the face recognition and attendance marking process.

## 🤝 Contributions

Your contributions are always welcome! Feel free to improve the code, suggest new features, or report any issues.


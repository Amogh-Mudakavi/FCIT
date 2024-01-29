# Face_recognition_ESP_32

**Project Title: Face Recognition Attendance System using ESP32 CAM**

**Overview:** This project implements a Face Recognition Based Attendance System using the ESP32 CAM Module, OpenCV, and Python. It utilizes OpenCV for image processing and Visual Studio as the integrated development environment (IDE). The system captures images, detects faces, recognizes individuals, and records attendance data into a Microsoft Excel file.

**Features:**

-   Real-time face detection and recognition.
-   Attendance marking with timestamps.
-   Compatibility with ESP32 CAM Module and OpenCV libraries.
-   Easily customizable and extendable for various applications.

**Installation:**

1.  Ensure Python is installed on your system.
2.  Install necessary libraries using pip:
    
    Copy code
    
    `pip install pandas opencv-python-headless numpy face_recognition` 
    
3.  Connect the ESP32 CAM Module and ensure it's accessible over the network.
4.  Update the URL variable in the Python script with the ESP32 CAM Module's IP address.
5.  Place images of known individuals in the specified directory.

**Usage:**

1.  Run the Python script in a compatible environment:
    
    Copy code
    
    `python face_recognition_attendance.py` 
    
2.  Stand in front of the ESP32 CAM Module for face detection and recognition.
3.  Monitor the console output for attendance marking updates.
4.  Access the "Attendance.csv" file generated in the working directory for attendance records.
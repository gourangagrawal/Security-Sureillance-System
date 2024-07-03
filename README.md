# Security-Sureillance-System
This Python-based security surveillance system utilizes the OpenCV library to create a robust solution for detecting intruders. Employing the frame difference technique of background subtraction ensures precise motion detection, crucial for identifying unauthorized movements in real-time. To enhance the quality of captured images, the system applies Gaussian blur and converts frames to grayscale, optimizing detection accuracy. This project serves as a foundation for developing effective home security systems, emphasizing simplicity and efficiency in monitoring and alerting users to potential threats.

# Key Features:

Motion Detection: Utilizes frame difference technique of background subtraction for accurate motion detection.
Image Enhancement: Applies Gaussian blur and grayscale conversion for improved image quality and detection accuracy.

# Usage:

Requirements: Python 3.x, OpenCV library.

Installation: Clone the repository and install dependencies (pip install -r requirements.txt).

Execution: Run main.py to start the security camera.

# How It Works:

Motion Detection: Compares consecutive frames to detect changes, indicating potential intrusions.
Image Enhancement: Preprocesses frames with Gaussian blur to reduce noise and converts to grayscale for better feature extraction.

# Acknowledgments:

Built with Python and OpenCV.
Inspired by the need for effective home security systems.

# Future Improvements:

Implement object tracking for continuous monitoring.
Integrate with cloud storage for remote access to footage.

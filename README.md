# Motion Detection using OpenCV

A Python-based motion detection system that identifies movement in real time using video frames.
The project demonstrates how to apply computer vision techniques for detecting and tracking motion events through frame differencing, thresholding, and contour detection.

 Technologies Used

Language: Python

Libraries: OpenCV, NumPy, datetime

Environment: Jupyter Notebook

 Project Overview

The system compares consecutive frames from a video stream to detect motion.
When motion is detected, the frame difference is highlighted, and the time of the event is recorded for further analysis.

Key Steps:

Captured frames from video input using OpenCV.

Converted frames to grayscale and applied Gaussian blur for noise reduction.

Used frame differencing and contour detection to identify motion areas.

Highlighted motion regions and logged timestamps for detected events.

 Output

Detects and highlights moving objects in real-time video.

Records event timestamps for each motion detected.

Can be extended for security cameras, surveillance, or automation tasks.

 How to Run

Clone the repository

git clone https://github.com/sai15235/motion-detection.git


Navigate to the project folder

 ### cd motion-detection


Install dependencies

### pip install opencv-python numpy


Run the script

### python motion_detection.py

 Future Enhancements

Add object tracking for multiple motion zones

Integrate email or SMS alert notifications

Save motion frames automatically to cloud storage


 Author

Saikiran Reddy
 Hyderabd, India
🔗 linkedin.com/in/saikiran-r717
 | saikiranr717@gmail.com

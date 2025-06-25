🧠 Real-Time Face Detection using OpenCV
This project demonstrates real-time face detection using OpenCV and Python.
It utilizes the Haar Cascade Classifier provided by OpenCV to detect human faces from live webcam video feed.

📸 Features
Captures live video stream using your system's webcam.
Detects faces using Haar Cascades.
Draws bounding boxes around detected faces.
Stops the video stream when the user presses the 'a' key.

🧰 Technologies Used
Python 3.12
OpenCV (cv2)

🔍 How it Works
The webcam feed is accessed using cv2.VideoCapture(0).
Each frame is converted to grayscale.
Haar cascade classifier detects face locations.
Bounding boxes are drawn around detected faces.
Press a to stop the video feed.

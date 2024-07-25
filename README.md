# Volume-Control-Using-Hand-Gesture
Project Description
Volume Control Using Hand Gesture

This project allows users to control the system volume using hand gestures captured by a webcam. By leveraging computer vision and machine learning techniques, it detects specific hand movements and adjusts the volume accordingly. The project utilizes OpenCV for video capture and Mediapipe for hand tracking, combined with the Pycaw library to interface with the system's audio controls.

Features Description
Hand Gesture Detection: Uses Mediapipe's hand tracking module to detect and track hand landmarks in real-time.
Volume Control: Adjusts the system volume based on the distance between the thumb and index finger. The closer the fingers are, the lower the volume; the farther apart, the higher the volume.
Visual Feedback: Provides real-time visual feedback by displaying the current volume percentage and a volume bar on the video feed.
Installation Description
Dependencies

OpenCV: Library for computer vision tasks, used here for capturing and processing video frames.
Mediapipe: Framework for building multimodal machine learning pipelines, used here for hand tracking.
Pycaw: Python library for audio control, used here to interface with the system's audio settings.
Numpy: Library for numerical computations, used here for calculations involving hand landmarks.

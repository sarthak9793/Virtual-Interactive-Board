# Introduction

The Streamlit WebCam App is an interactive application designed to capture video from a webcam, process the video stream in real-time to detect hand gestures, and use these gestures to draw on a virtual canvas.

## Key Features
* Real-Time Video Capture: Utilizes the OpenCV library to capture live video feed from the user's webcam, allowing for the real-time interaction and processing of video frames.
* Hand Gesture Recognition: Integrates MediaPipe's hand tracking solution to recognize hand gestures within the video feed. This feature enables the application to interpret specific movements and positions of the user's hand as commands for drawing on the virtual canvas.
* Interactive Drawing Canvas: Provides a virtual canvas where users can draw using their hand gestures. The application translates recognized gestures into drawing actions, allowing users to change colors and draw on the canvas without physical contact.
* Color Selection and Drawing Tools: Supports multiple drawing colors and implements a mechanism for the user to select different colors through hand gestures. The application's UI includes designated areas for color selection, which the user can interact with directly through the video feed.
* Clear Canvas Functionality: The application includes a "Clear" button within the virtual drawing interface, allowing users to easily reset their canvas and start a new drawing without manual erasure, enhancing user experience by providing a quick way to restart creative projects.

## High-Level Architecture
![image](https://github.com/sarthak9793/Virtual-Interactive-Board/assets/75237194/6923f114-eec3-4ae3-b92b-0a929ac7bfc1)

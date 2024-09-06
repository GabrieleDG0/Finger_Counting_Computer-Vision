# Finger counting with OpenCV and MediaPipe

## Introduction
This project is a real-time finger counting application that uses OpenCV for video capture and MediaPipe for hand feature recognition. The application captures video from the webcam, recognizes the position of the fingers and displays the number of fingers raised on the screen.

**Note: You can find a .exe file, inside the release section of Github, if you want to try the project, without needing to install Python, if you have a Windows system.**

### Controls
- Q Key: Exit and close all the windows 

## Features
- Real-time finger recognition: The application recognizes the number of fingers raised in real time using your webcam.
- Hand tracking: The application uses MediaPipe's hand tracking solution to detect and track the position of the fingers.
- FPS display: The application displays frames per second (FPS) on the screen to monitor performance.
- Customizable: The script includes settings for camera resolution, detection security and tracking security.

## Environment considerations
For optimal performance, make sure you are using the application in an environment with the following conditions:

- Good lighting: avoid strong light or reflections that can cause glare. Soft, even lighting is best for hand feature recognition.
- Neutral background: A simple, unobtrusive background is ideal to reduce noise and ensure accurate hand recognition.
- Minimal movement: Keep the camera and hand still during recognition to maintain accuracy.

### Setup and configuration
1. Prerequisites
To run this script, you must have Python and the following packages installed:
- OpenCV
- MediaPipe

### Landmarks model
![Landmarks](https://github.com/user-attachments/assets/64b5c2ab-15a7-49f0-9241-e0e4dda6498b)

## Applications and future extensions

### Applications
- Gesture control: This finger counting application can be extended to develop gesture-based controls for various applications such as controlling multimedia, interacting with smart home devices or even games.
- Educational tools: The application can be used as a teaching tool to teach counting, arithmetic operations or basic programming concepts related to computer vision and AI.
- Sign language recognition: With further development, the system could be improved to recognize more complex hand gestures, potentially leading to a sign language interpretation tool.

### Future enhancements
- Multi-hand support: The application could be enhanced to recognize and count the fingers of multiple hands simultaneously, which would be useful for collaborative gestures or multi-user interaction.
- Recognise gestures: Beyond counting, implement recognition of various hand gestures, such as thumbs up, victory signs, or other common gestures to perform specific actions or commands.
- Integration of augmented reality (AR): Integrate the app with AR to create an interactive experience where digital objects respond to hand gestures and finger counting.
- Fitness and health monitoring: Develop a system that uses finger gestures to interact with fitness applications, such as tracking workout repetitions or controlling exercise routines.
- Machine learning integration: Train a custom machine learning model to improve the accuracy and speed of finger and gesture recognition, especially in different lighting conditions and backgrounds.

This project serves as a solid foundation for the research and further development of fingerprint and gesture recognition technologies in various fields. If you find any bugs, errors or problems, feel free to open an issue. **Happy Coding!**

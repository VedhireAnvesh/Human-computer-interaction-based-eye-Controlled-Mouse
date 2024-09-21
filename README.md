Human Eye-Controlled Mouse
This project is designed to control a computer mouse using the movements of the human eye. It leverages computer vision, machine learning, and open-source libraries to track eye movements and translate them into corresponding mouse actions, such as moving the cursor, clicking, or scrolling. The project aims to provide an alternative, hands-free way of controlling a computer, making it especially useful for individuals with physical disabilities.

More Information about the Project
The system captures real-time video input from a camera (usually a webcam) and uses computer vision techniques to detect and track the user's eyes. Machine learning models are used to identify the direction of the gaze and map that to specific mouse movements or actions.

The project ensures accurate tracking by using OpenCV for image processing and dlib for face and eye detection. The highly customizable system allows users to adjust sensitivity and calibration to match their preferences.

Key Features:
Real-Time Eye Tracking:

The system captures and processes real-time video to detect and track the user's eyes using OpenCV and dlib.
Mouse Control:

Eye movements are translated into mouse cursor movements, allowing users to move the cursor across the screen.
Eye blinks or prolonged gazes can be programmed to perform clicking and scrolling actions.
Calibration:

A calibration feature allows users to fine-tune the system for more precise control, adapting to different lighting conditions and user-specific parameters.
Libraries Used:
OpenCV (for video capture and image processing)
dlib (for face and eye detection)
numpy (for numerical computations)
pyautogui (for controlling the mouse)
Installing Required Packages:
bash
Copy code
pip install opencv-python dlib numpy pyautogui
How to Run:
Set up the webcam and make sure it is positioned so that your eyes are clearly visible.
Run the main Python script that initializes the webcam and starts capturing and processing eye movements:
bash
Copy code
python eye_controlled_mouse.py
Calibrate the system by following the on-screen instructions to adjust tracking parameters for your specific environment.
Start controlling the mouse with your eye movements!
Project Structure:
eye_controlled_mouse.py - Main file for running the eye-controlled mouse.
calibration.py - Script for fine-tuning and calibrating eye detection parameters.
utils.py - Utility functions for eye tracking and gaze estimation.

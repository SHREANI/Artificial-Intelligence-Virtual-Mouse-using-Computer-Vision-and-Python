# Artificial-Intelligence-Virtual-Mouse-using-Computer-Vision-and-Python
This project replaces the traditional physical mouse with an AI-powered virtual mouse controlled entirely through hand gestures using a standard webcam. It leverages computer vision and machine learning to detect and track hand movements in real time, allowing users to perform mouse operations without touching any hardware.
🔹 Features
Contactless Control – Operate your computer without a physical mouse.
Real-Time Hand Tracking – Uses OpenCV and MediaPipe for accurate hand landmark detection.
Gesture Recognition – Specific gestures trigger mouse actions (e.g., index finger up = move cursor, pinch = click).
Cross-Platform – Works on Windows, macOS, and Linux.
Customizable Gestures – Easily modify code to add new controls.

🔹 How It Works
Camera Feed Processing – Captures live video from the webcam.
Hand Detection & Landmark Mapping – Detects the hand and its key points using MediaPipe Hands.
Gesture Interpretation – Maps detected gestures to mouse functions.
Mouse Control Execution – Uses the PyAutoGUI library to perform actual cursor and click actions.

🔹 Tech Stack
Python
OpenCV – Image processing and video capture.
MediaPipe – Hand tracking and landmark detection.
PyAutoGUI – Simulating mouse actions.
NumPy – Numerical operations for coordinate mapping.

🔹 Applications
Touchless control for hygiene-sensitive environments.
Accessibility tool for people with mobility impairments.
Fun, interactive gesture-based interfaces for projects and presentations.

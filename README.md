Title of the Project
The Drowsiness Detection System is a real-time solution designed to monitor eye states and detect signs of drowsiness using computer vision and deep learning.

About
The project on real-time drowsiness detection aims to enhance safety by monitoring eye states through a webcam, employing deep learning techniques. Utilizing a convolutional neural network (CNN), the system classifies eye states as "open" or "closed" in real-time, triggering alerts if prolonged eye closure is detected. The approach focuses on cost-effectiveness by using standard hardware like webcams and Haar cascade classifiers for face and eye detection.
Features
Continuous Real-Time Monitoring: The system captures live video feed from a standard webcam, enabling uninterrupted monitoring of the user's eye states.

Deep Learning-Based Eye State Classification: It employs a convolutional neural network (CNN) to analyze grayscale images of the eyes and accurately classify them as "open" or "closed." This classification is essential for identifying signs of drowsiness.

Alert Mechanism: The system is equipped with auditory alarms and visual alerts that activate when prolonged eye closure is detected. This helps to promptly alert the user, reducing the risk of accidents caused by drowsiness
Requirements
Operating System: Compatible with common operating systems like Windows, macOS, or Linux. Programming Language: Python is used for implementing the system. Deep Learning Framework: TensorFlow or Keras to build and train the convolutional neural network (CNN) model. Computer Vision Library: OpenCV is used for real-time video processing, face, and eye detection. Audio Library: Pygame or other audio libraries for handling alert sounds. IDE (Integrated Development Environment): Tools like Visual Studio Code or PyCharm for coding and development.
System Architecture


Output
Output1 - A score is displayed on the screen, increasing when eyes are closed and decreasing when they are open.


Output2 - The system classifies the user's eye state as "Open" or "Closed" for each frame captured from the webcam.


Accuracy (90%): The system correctly identifies whether a person is drowsy or alert in 90% of the cases.
Results and Impact
The real-time drowsiness detection system successfully demonstrated its ability to monitor and alert individuals about potential drowsiness. The results show that the system can accurately classify eye states as "open" or "closed" in real-time using a convolutional neural network (CNN). By continuously analyzing video frames captured from a webcam, the system effectively identifies prolonged eye closure, which may indicate drowsiness, and triggers auditory and visual alerts to prompt the user to regain alertness.
Articles published / References
1)Florez, Ruben, et al. "A CNN-Based Approach for Driver Drowsiness Detection by Real-Time Eye State Identification." Applied Sciences, vol. 13, no. 13, 2024.
2)Florez, R., Palomino-Quispe, F., Coaquira-Castillo, R. J., & Paixão, T. (2024). A CNN-Based Approach for Driver Drowsiness Detection by Real-Time Eye State Identification. Applied Sciences, 13(13), 7849-7860.

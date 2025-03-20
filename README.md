# BE-Project
Heartbeat Detection Using Machine learning[B.E.-2022]
In this system to detect the person's heartbeat first person's face detected using face detection algorithm using web cam.Then display heartbeat in BPM. 
This system detects a person's heartbeat using a webcam and machine learning techniques. It works by analyzing subtle changes in the facial skin color, which correspond to blood flow variations.

Working Process
Face Detection:

The system uses a face detection algorithm (e.g., OpenCV, Dlib, or MediaPipe) to detect the person’s face in real time.
Heartbeat Extraction:

It captures subtle changes in skin tone caused by blood circulation using Remote Photoplethysmography (rPPG).
Signal processing techniques such as Eulerian Video Magnification (EVM) enhance these variations.
Machine Learning Model:

A pre-trained model processes the extracted signal and estimates the heart rate.
Deep learning techniques (CNNs/RNNs) can improve accuracy.
BPM Display:

The calculated heartbeat (BPM) is displayed on the screen.
Technologies Used
Python (OpenCV, NumPy, TensorFlow/PyTorch)
Face Detection (Haar cascades, Dlib, or MediaPipe)
Machine Learning for Signal Processing
Flask/Django (Optional, for Web Integration)
Use Cases
Health Monitoring
Fitness Tracking
Contactless Heart Rate Measurement

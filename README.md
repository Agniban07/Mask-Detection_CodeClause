# Mask-Detection_CodeClause
Real-time face mask detection using Python, Keras, and OpenCV for promoting safety and compliance. Detects masks in video streams with bounding boxes. 
Overview:
Our Face Mask Detection project is a real-time solution designed to identify individuals wearing or not wearing face masks using Python, Keras, and OpenCV. With the ongoing importance of face masks in public health, this project provides a practical tool for enforcing mask-wearing policies.

Key Features:

Real-time Video Stream: We leverage OpenCV to capture and process video streams from webcams or other sources, ensuring efficient real-time monitoring.

Deep Learning Model: We've built a robust convolutional neural network (CNN) using Keras, which accurately classifies faces as 'with mask' or 'without mask'.

Face Detection: OpenCV is employed to locate and extract faces from each frame of the video stream, preparing them for mask detection.

Mask Detection: Our deep learning model then classifies these extracted faces to determine whether a mask is present.

Visual Feedback: Bounding boxes and labels are superimposed on the video stream to indicate the presence or absence of masks, making it easy to identify non-compliance.

Real-time Alerts: In situations where individuals are not wearing masks, the system can trigger alerts or notifications to ensure prompt action.

Getting Started:

Clone the repository.
Set up a Python environment with dependencies (see requirements.txt).
Run the main script to initiate real-time face mask detection on your preferred video source.
Contributing:
We welcome contributions! Fork the repository, create new features, enhance existing ones, and submit pull requests to improve the project.

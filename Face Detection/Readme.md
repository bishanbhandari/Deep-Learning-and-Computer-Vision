### Face Detection Using Haar Cascade and MTCNN

Overview

This project explores two face detection techniques: Haar Cascade and MTCNN (Multi-task Cascaded Convolutional Networks) using Python and computer vision libraries.

The project detects human faces in images, extracts bounding box coordinates, and visualizes detected faces using OpenCV.

Technologies Used

Python

OpenCV

MTCNN

NumPy

Pandas

Matplotlib

tqdm

Detection Methods

### Haar Cascade

Traditional machine learning-based face detection.

Uses a pre-trained XML classifier.

Detects faces using detectMultiScale().

### MTCNN

Deep-learning-based face detection.

Uses three networks: P-Net, R-Net, and O-Net.

Detects faces, refines bounding boxes, and identifies five facial landmarks.

### Project Workflow

Load and organize facial image datasets.

Preprocess and visualize sample images.

Apply Haar Cascade for face detection.

Apply MTCNN for face detection.

Draw bounding boxes around detected faces.

Examine and compare detection results.
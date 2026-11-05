# Eye Disease Classification

## Overview
This project uses Deep Learning and Computer Vision to classify eye disease images using a Convolutional Neural Network (CNN).

It uses **ResNet34** with Transfer Learning through the fastai library.

## Technologies Used
- Python
- PyTorch
- fastai
- ResNet34
- Jupyter Notebook

## Workflow
1. Load and prepare the eye disease dataset.
2. Split images into training and validation sets (80/20).
3. Resize images to 192 × 192 pixels.
4. Build a classification model using pretrained ResNet34.
5. Fine-tune the model for 50 epochs.
6. Evaluate model performance using accuracy.

## Model Training

```python
learn = vision_learner(dls, resnet34, metrics=accuracy)
learn.fine_tune(50)
```

## Future Improvements
- Experiment with different CNN architectures.
- Improve model accuracy.
- Evaluate using additional performance metrics.
- Develop a web application for image classification.

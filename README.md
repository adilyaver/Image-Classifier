# Image Classifier

This repo contains the code to train a Convolutional Neural Network to distinguish between cat and dog images.

---

## Features To be Added

* Custom CNN model built using Pytorch
* Transfer Learning model using MobileNetV2
* Training/validation pipeline with plots
* Model performance comparison (accuracy, precision and recall) 
* Ready-to-use prediction script for images
* Webcam Cat–Dog Detector that draws bounding box + prediction label on the video
---

##  Project Structure

```
├── data/
│   ├── train/
│   ├── valid/
│   └── test/
├── models/
│   ├── cnn_model.h5
│   └── mobilenet_model.h5
├── notebooks/
│   └── training_experiments.ipynb
├── scripts/
│   ├── train_cnn.ipynb
│   ├── train_mobilenet.ipynb
│   ├── test.ipynb
│   └── webcam_classifier.py
├── utils/
│   └── gradcam.py
└── README.md
```

---

## Installation

### Requirements

* Python 3.9+
* Pytorch
* NumPy
* Matplotlib
* OpenCV (for webcam mode)

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Dataset

* Kaggle cat and dog dataset : https://www.kaggle.com/datasets/tongpython/cat-and-dog

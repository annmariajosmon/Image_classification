# Celebrity Image Classification using CNN

## Overview

This project is a deep learning-based celebrity image classification system developed using Python, OpenCV, TensorFlow, and Keras. The application classifies celebrity images into multiple categories using Convolutional Neural Networks (CNNs).

The model was trained on a dataset of cropped celebrity images with data augmentation techniques to improve performance and generalization.

---

## Features

- Celebrity image classification using CNN
- Image preprocessing using OpenCV
- Data augmentation using ImageDataGenerator
- Deep learning model training and evaluation
- Multi-class image prediction
- Model saving and loading using `.h5`
- Prediction pipeline using Jupyter Notebook

---

## Technologies Used

- Python
- OpenCV
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Deep Learning
- Computer Vision

---

## Dataset Classes

- Lionel Messi
- Maria Sharapova
- Roger Federer
- Serena Williams
- Virat Kohli

---

## Data Preparation

- Image files are collected from the dataset directory.
- File paths and labels are organized using a Pandas DataFrame.
- The dataset is split into training, validation, and test sets.

---

## Data Augmentation

Image augmentation techniques applied to the training dataset include:

- Rescaling
- Shearing
- Zooming
- Horizontal Flipping

Validation and test datasets are only rescaled.

---

## CNN Architecture

The CNN model consists of:

- Convolutional Layers (Conv2D)
- ReLU Activation Functions
- MaxPooling Layers
- Flatten Layer
- Dense Fully Connected Layers
- Dropout Layer
- Softmax Output Layer

---

## Model Training

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Evaluation Metric: Accuracy
- Epochs: 10

---

## Model Evaluation

The trained model is evaluated on the test dataset to measure classification accuracy.

---

## Model Saving

The trained CNN model is saved as:

```text
sports_person_model.h5
```

The class mapping is saved as:

```text
class_dictionary.json
```

---

## Prediction Workflow

```text
Input Image
      ↓
OpenCV Preprocessing
      ↓
Image Resizing & Normalization
      ↓
CNN Model Prediction
      ↓
Celebrity Classification Output
```

---

## Repository Structure

```text
celebrity-image-classification-cnn/
│
├── README.md
├── celebrity_prediction.ipynb
├── class_dictionary.json
├── requirements.txt
├── sports_person_model.h5
│
└── Image_classification-main/
    │
    ├── cnn_training_model.py
    └── cropped/
```

---

## Installation

Install required libraries using:

```bash
pip install -r requirements.txt
```

---

## Run the Training Script

```bash
python cnn_training_model.py
```

---

## Run Prediction Notebook

Open:

```text
celebrity_prediction.ipynb
```

and run all cells.

---

## Applications

- AI-based image classification
- Celebrity recognition systems
- Computer vision applications
- Face recognition projects
- Deep learning learning projects

---

## Future Improvements

- Real-time webcam celebrity recognition
- Face detection integration using OpenCV
- Transfer learning using pretrained models
- Web deployment using Flask or Streamlit

---

## Author

ANN MARIA JOSMON

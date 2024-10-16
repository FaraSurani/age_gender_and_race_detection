# Age, Gender, and Race Detection Using CNNs

This repository contains a deep learning project that uses Convolutional Neural Networks (CNNs) for detecting and classifying the age, gender, and race of individuals from facial images. The model is trained on the UTKFace dataset, a large-scale dataset containing images labeled with age, gender, and race attributes.

## Key Features:
- **Dataset**: The UTKFace dataset is used, which includes thousands of images labeled for age, gender, and race.
- **Model**: A deep learning model built using TensorFlow/Keras, incorporating convolutional layers, pooling layers, and dropout for robust classification.
- **Preprocessing**: Images are preprocessed by resizing and normalization before being input into the CNN model.
- **Multi-task Learning**: The model performs multi-task learning by predicting age, gender, and race in one go.

## Setup Instructions:
1. Download the dataset from Kaggle: [UTKFace Dataset](https://www.kaggle.com/datasets/jangedoo/utkface-new).
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt

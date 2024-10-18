# Brain Tumor MRI Classification

## Overview
This project implements a Convolutional Neural Network (CNN) to classify MRI brain scans as either containing a tumor or being tumor-free. Leveraging deep learning techniques, this model provides an effective tool for aiding medical professionals in the early detection of brain tumors.

 
## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Results](#results)
- [Future Work](#future-work)


## Features

- **High Accuracy**: Achieved significant accuracy in classifying brain tumors from MRI scans.
- **Data Preprocessing**: Implemented techniques such as resizing, normalization, and data augmentation.
- **Interactive Interface**: Created a Gradio interface for easy user interaction and real-time predictions.
- **Confidence Scores**: Provides users with confidence levels for each prediction.
- 
## Technologies Used
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white) 
![TensorFlow](https://img.shields.io/badge/TensorFlow-E03C31?style=for-the-badge&logo=tensorflow&logoColor=white) 
![Gradio](https://img.shields.io/badge/Gradio-FF5A5F?style=for-the-badge&logo=gradio&logoColor=white) 
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) 
![Matplotlib](https://img.shields.io/badge/Matplotlib-003B57?style=for-the-badge&logo=matplotlib&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)


## Dataset
The model is trained using the [Brain Tumor MRI Dataset](https://www.kaggle.com/masoudnickparvar/brain-tumor-mri-dataset) from Kaggle. This dataset consists of MRI images categorized into:
- Tumor
- No Tumor
  
## Training
* Epochs: 10
* Optimizer: Adam

![image](https://github.com/user-attachments/assets/20682622-0890-48af-9884-863cf7fce47f)

## Gradio Interface
![image](https://github.com/user-attachments/assets/4d1b3e18-4195-45a2-8663-723ace7bc284)












## Installation

To set up this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone <repository_url>
    cd brain-tumor-classification
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the model training script to train the CNN:
    ```bash
    python train.py
    ```

2. Launch the Gradio interface:
    ```bash
    python app.py
    ```

3. Access the web interface at `http://127.0.0.1:7860` (or the provided public link) to upload MRI images and see predictions.

## Model Training

- The model is trained using a set of hyperparameters optimized for the dataset.
- Data augmentation techniques are employed to enhance the training dataset and improve model robustness.

## Results

- The model achieved a high accuracy rate in classifying MRI scans, indicating its potential for clinical application.

## Future Work

- Explore advanced CNN architectures for potentially improved performance.
- Expand the dataset to include more diverse MRI scans for better generalization.
- Enhance the Gradio interface with additional features and functionalities.







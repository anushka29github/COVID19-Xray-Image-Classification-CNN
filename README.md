# COVID19-Xray-Image-Classification-CNN
This repository contains a convolutional neural network (CNN) model to detect COVID-19 from X-ray images. The model is built using TensorFlow and Keras and aims to help in the early detection of COVID-19 through chest X-rays.

## Features
- Data preprocessing
- CNN architecture for image classification
- Training and validation of the model
- Evaluation metrics to assess model performance
- Instructions for reproducing the results

## Dataset

### Source
The dataset used for this project is sourced from [Kaggle's COVID-19 Radiography Database](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database). This dataset contains chest X-ray images of patients diagnosed with COVID-19, Viral Pneumonia, and Normal cases.

### Description
- **Total Images**: The dataset consists of 15,000 X-ray images.
- **Classes**: 
  - COVID-19: 3616 images
  - Viral Pneumonia: 1345 images
  - Normal: 10192 images
 
The model was trained on the COVID-19 Radiography Database and achieved the following performance metrics:

- **Validation Accuracy**: 95.92%
- **Training Accuracy**: 97.08%
- **Loss**: 0.793

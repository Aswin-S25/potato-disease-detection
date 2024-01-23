# Potato Disease Prediction using CNN and FastAPI

## Overview

This repository contains a Deep Learning (DL) model implemented using Convolutional Neural Networks (CNN) for classifying images of potato leaves into three categories: Early Blight, Healthy, and Late Blight. Additionally, it includes a FastAPI backend API for seamless integration and deployment.

## Contents

1. **CNN Model:**
   - The core of the project is a trained CNN model capable of accurately classifying potato leaf images into different disease categories. The model is trained on a labeled dataset with examples of Early Blight, Healthy, and Late Blight instances.

2. **Dataset:**
   - The dataset used for training and evaluating the model is included in the repository. It comprises a diverse set of potato leaf images, carefully labeled for each disease category.

3. **Training Script:**
   - The script used for training the CNN model is provided. It includes data preprocessing, model architecture, training, and evaluation procedures.

4. **FastAPI Backend:**
   - The FastAPI backend serves as an interface for making predictions with the trained model. It exposes endpoints for uploading images and receiving predictions in real-time.

5. **Documentation:**
   - Detailed documentation is available to guide users on setting up the project, training the model, and deploying the FastAPI backend.

## Usage

1. **Model Training:**
   - Follow the provided documentation to train the CNN model using the provided dataset or your own dataset.

2. **FastAPI Deployment:**
   - Deploy the FastAPI backend using the instructions in the documentation. The API enables users to send images and receive predictions on the potato leaf's health status.

3. **Integration:**
   - Integrate the trained model and FastAPI backend into your applications, services, or websites for real-time potato disease prediction.

## Requirements

- Python 3.7+
- TensorFlow or PyTorch (depending on the chosen DL framework)
- FastAPI
- Uvicorn (ASGI server)

## Contributions

Contributions are welcome! If you encounter issues or have improvements to suggest, feel free to open an issue or submit a pull request.

This detailed description provides potential users and contributors with a comprehensive understanding of your project, its components, and how to use them. Make sure to keep the documentation up-to-date as you evolve your project.

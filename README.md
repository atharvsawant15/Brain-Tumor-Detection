# Brain Tumor Detection Web Application

This project is a **Flask-based web application** that detects brain tumors from MRI images using multiple machine learning models.  
Users can upload an MRI scan image and the system will predict the tumor type.

## Features
- Upload MRI brain scan images
- Predict tumor type using **three different models**
- Display prediction probabilities
- Simple and interactive web interface

## Tumor Classes
The system predicts the following categories:

- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

## Models Used
The application uses three machine learning models:

1. **Convolutional Neural Network (CNN)**
2. **Logistic Regression**
3. **Support Vector Machine (SVM)**

Each model predicts the tumor type and displays probability scores.

## Technologies Used

- Python
- Flask
- TensorFlow / Keras
- Scikit-learn
- OpenCV
- NumPy
- HTML / CSS / JavaScript
- Gunicorn (for deployment)

## Project Structure

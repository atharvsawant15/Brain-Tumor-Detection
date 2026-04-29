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

## Installation
1. Clone the repository:

git clone https://github.com/atharvsawant15/Brain-Tumor-Detection

cd brain-tumor-detection


2. Create a virtual environment (optional):

python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate


3. Install dependencies:

pip install -r requirements.txt


## Usage
Run the Flask app:

python app.py


Open your browser and go to:

http://127.0.0.1:5000/


Upload an MRI image and view predictions.

## Output
- Predicted tumor type  
- Probability scores from each model  
- Display of uploaded image  

## Deployment
You can deploy using:
- Gunicorn  
- Heroku / Render / Railway  

Run with:

gunicorn app:app


## Future Improvements
- Add advanced deep learning models  
- Improve accuracy with larger datasets  
- Add Grad-CAM visualization  
- Add user authentication  

## Contributing
Contributions are welcome. Feel free to fork the repository and submit a pull request.

## License
This project is open-source and available under the MIT License.

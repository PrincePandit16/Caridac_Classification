# Caridac-Classification

Cardiac Classification Web App

#Overview

This project is a Flask-based web application that allows users to upload medical images and classify them into predefined cardiac categories using a deep learning model. The model, implemented with TensorFlow/Keras, is trained to identify various cardiac structures from medical imaging data.

#Features

Web-based interface for image upload and classification

Model prediction using a pre-trained TensorFlow/Keras model (my_model.h5)

#Logging of uploaded image filenames (app.log)

Image preprocessing with OpenCV and PIL

#Installation

Prerequisites

Ensure you have the following installed:

Python 3.8+

Flask

TensorFlow/Keras

OpenCV

Pillow (PIL)

#Setup Instructions

Clone this repository:

git clone https://github.com/your-username/cardiac-classification.git
cd cardiac-classification

Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

#Install dependencies:

pip install -r requirements.txt

Ensure my_model.h5 is in the project directory.

#Usage

Run the Flask application:

python app1.py

Open a browser and navigate to http://127.0.0.1:5000/

Upload an image for classification.

#File Structure

/cardiac-classification
│── app1.py                 # Flask application
│── my_model.h5             # Pre-trained model
│── templates/
│   ├── index.html          # HTML for UI
│── static/
│   ├── styles.css          # CSS for styling (if any)
│── app.log                 # Log file for uploaded images
│── requirements.txt        # Python dependencies
│── README.md               # Project documentation

#Logs

Uploaded images are logged in app.log with their filenames:

2025-01-03 05:00:24,066 INFO Input filename: temp_image.jpg

#Future Improvements

Enhance model accuracy with more training data

Deploy on cloud platforms (AWS, GCP, or Heroku)

Implement a better UI/UX

#License

This project is open-source under the MIT License.

#Contact

For questions or contributions, feel free to create an issue or a pull request on GitHub.


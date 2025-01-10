Overview

This project is a Brain Tumor Detection web application that uses machine learning and deep learning to classify MRI scans and detect the presence of a brain tumor. It provides an easy-to-use interface for uploading images and viewing results.

Features

Upload MRI Scans: Upload your MRI scan images for analysis.

Tumor Detection Results: Get instant feedback on whether a tumor is detected or not.

Health Tips: Offers recommendations for maintaining a healthy lifestyle and routine check-ups.

Secure Login: Sign up or log in securely to access your personalized dashboard.

Responsive Design: Optimized for various devices and screen sizes.

Technologies Used

Frontend:

HTML5, CSS3, Bootstrap

JavaScript

Backend:

Flask (Python)

TensorFlow/Keras for model integration

Database:

SQLite for user authentication and data storage

Setup and Installation

Follow these steps to run the project on your local machine:

Clone the repository:

git clone https://github.com/Swastika708/Brain-Tumour
cd Brain-Tumour

Set up a virtual environment:

python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`

Install dependencies:

pip install -r requirements.txt

Run the application:

python app.py

Access the application:
Open your browser and go to http://127.0.0.1:5000.

How It Works

Upload an MRI scan image via the web interface.

The backend processes the image using a pre-trained deep learning model.

Results are displayed, indicating whether a tumor is detected along with health tips.

Screenshots

Upload Page

Result Page


Integration with cloud services for faster processing.

Adding support for other medical imaging modalities.

Improved accuracy with advanced deep learning models.

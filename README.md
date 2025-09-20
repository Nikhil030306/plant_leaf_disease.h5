Plant Disease Detection using Deep Learning & Streamlit

This project detects plant diseases from leaf images using deep learning and provides predictions through a simple Streamlit web app.
Users can upload an image or capture one using their camera for real-time detection.

Features

Image classification using transfer learning (MobileNetV2 / EfficientNet)

Data preprocessing with augmentation (rotation, zoom, flip, rescale)

Interactive Streamlit web app for predictions

Camera support for real-time leaf capture

Easy to use and well-documented

Tech Stack

Python

TensorFlow / Keras

NumPy

Pillow (PIL)

Streamlit

Matplotlib / Seaborn

Project Structure
plant-disease-detection/
│
├── dataset/                  # Train & Test dataset
│   ├── train/
│   └── test/
│
├── plant_disease_model.h5    # Trained Model
├── app.py                    # Streamlit Web App
├── train_model.ipynb         # Training Notebook
├── requirements.txt          # Dependencies
└── README.md                 # Project Documentation

How to Run

Clone the repository:

git clone https://github.com/yourusername/plant-disease-detection.git
cd plant-disease-detection


Install dependencies:

pip install -r requirements.txt


Run the Streamlit app:

streamlit run app.py

Future Improvements

Add more plant species and diseases

Deploy on Streamlit Cloud or Hugging Face Spaces

Build a mobile-friendly interface

Acknowledgements

PlantVillage Dataset (Kaggle)

TensorFlow and Streamlit teams for amazing tools

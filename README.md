# 🩺 DermaScan AI: Skin Disease Detection

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow-orange)

## 📌 Project Overview
DermaScan AI is a Deep Learning project designed to detect skin diseases from images. Using Convolutional Neural Networks (CNN), the system analyzes skin lesions and predicts the disease class with high accuracy. This project aims to assist in early diagnosis.

## 🚀 Features
* **Image Upload:** Easy-to-use interface for uploading skin images.
* **AI Analysis:** Uses a trained CNN model to classify diseases (e.g., Melanoma, Eczema).
* **Instant Results:** Provides a probability score for the prediction.

## 🛠️ Tech Stack
* **Language:** Python
* **ML Framework:** TensorFlow / Keras
* **Interface:** Streamlit
* **Image Processing:** OpenCV, PIL

## 📂 Project Structure
* `app.py`: The main web application script.
* `train_model.py`: The script used to train the Neural Network.
* `requirements.txt`: List of dependencies.
* `model.h5`: The saved trained model (not included in repo due to size).

## 💻 How to Run
1. Clone the repo:
   ```bash
   git clone [https://github.com/akkkiee/SKIN_DISEASE_.git](https://github.com/akkkiee/SKIN_DISEASE_.git)

Install dependencies:
pip install -r requirements.txt

Run the app:
streamlit run app.py

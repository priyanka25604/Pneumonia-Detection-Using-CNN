🫁 Pneumonia Detection Using CNN

A deep learning project that detects Pneumonia from chest X-ray images using a Convolutional Neural Network (CNN). The model classifies images into Normal or Pneumonia, helping demonstrate how AI can assist in medical image diagnosis.

📌 Project Overview

This project builds and trains a CNN model on a publicly available chest X-ray dataset to perform binary image classification. It includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and prediction on new images.

🎯 Objective

To design and implement a CNN-based system that accurately classifies chest X-ray images as Normal or Pneumonia.

🗂 Dataset

Chest X-Ray Images (Pneumonia) – Kaggle

Link: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

Dataset Structure:

chest_xray/
 ├── train/
 │   ├── NORMAL/
 │   └── PNEUMONIA/
 ├── test/
 │   ├── NORMAL/
 │   └── PNEUMONIA/
 └── val/
     ├── NORMAL/
     └── PNEUMONIA/
🛠 Technologies Used

Python

TensorFlow / Keras

NumPy, Pandas

Matplotlib, Seaborn

OpenCV

🔍 Features

Image preprocessing and normalization

Exploratory Data Analysis (EDA)

CNN model training

Model evaluation using accuracy and loss

Prediction on custom X-ray images

🚀 How to Run

Clone this repository

git clone https://github.com/your-username/pneumonia-detection-cnn.git

Install dependencies

pip install -r requirements.txt

Run the Jupyter Notebook

jupyter notebook

Execute cells step-by-step.

📊 Model Workflow

Load Dataset

Preprocess Images

Build CNN Model

Train Model

Evaluate Performance

Test on New Images

✅ Sample Prediction Output
Prediction: PNEUMONIA

or

Prediction: NORMAL
📈 Results

The CNN model successfully learns visual patterns from X-ray images and achieves reliable accuracy in detecting pneumonia cases.

📌 Future Improvements

Add transfer learning (ResNet, EfficientNet)

Improve accuracy with data augmentation

Deploy as a web application

👩‍💻 Author

Priyanka Bendi


✅ Resume bullet points

Just tell me 😊

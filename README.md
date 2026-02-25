# mask-and-without-mask-detection-

😷 Face Mask Detection System

A Deep Learning–based Computer Vision project that detects whether a person is wearing a face mask or not using image classification techniques. This project demonstrates the practical implementation of Convolutional Neural Networks (CNN) for real-world safety monitoring applications.

📌 Project Overview

The Face Mask Detection System identifies human faces in images and classifies them into two categories:

✅ With Mask

❌ Without Mask

This solution can be used in public places such as airports, hospitals, offices, and schools to monitor compliance with safety guidelines.

🚀 Key Features
Face detection using OpenCV
Mask / No-Mask classification using Deep Learning
Image-based prediction
Easy to extend for real-time webcam detection
Clean and modular implementation in Jupyter Notebook

🛠️ Technologies Used
Python
OpenCV
TensorFlow / Keras
NumPy
Matplotlib
Jupyter Notebook

🧠 Project Workflow

Data Collection
 Images categorized into:
      With Mask
      Without Mask

Data Preprocessing
Image resizing
Normalization
Label encoding

Model Building
Convolutional Neural Network (CNN)
Activation functions (ReLU, Softmax)
Loss function & optimizer configuration

Model Training
Training on labeled dataset
Validation for performance monitoring

Prediction
Model predicts mask status on unseen images
Displays results with classification labels

📂 Project Structure
mask-and-without-mask-detection-/
│
├── detection_of_mask_and_without_mask_.ipynb   # Main project notebook
├── dataset/                                   # Training dataset (if added)
│   ├── with_mask/
│   └── without_mask/
└── README.md

📊 Model Performance
Achieves high classification accuracy on validation data
Can be improved further using:
Data augmentation
Transfer learning (MobileNetV2)
Larger dataset

🌍 Real-World Applications
Public safety monitoring
Workplace compliance systems
Healthcare facility monitoring
Smart surveillance systems

📈 Future Enhancements
Real-time webcam integration
Deployment using Flask / Streamlit
Cloud deployment
Mobile application integration

👩‍💻 Author
SHIVANI YADAV

# leaf-disease-prediction--Machine-Learning
Machine Learning-based Leaf Disease Prediction system using CNN. Classifies plant leaf images into multiple disease categories with high accuracy. Built using TensorFlow, OpenCV, and deployed with Streamlit for real-time predictions.
🌿 LeafD: AI-Powered Plant Leaf Disease Detection System
📌 Introduction

LeafD is a deep learning-based image classification system developed to detect plant leaf diseases from images. It uses transfer learning with EfficientNetB4 to achieve high accuracy while minimizing training time and computational cost.

This project demonstrates an end-to-end machine learning pipeline, from data preprocessing to model evaluation and prediction visualization.

🎯 Problem Statement

Manual identification of plant diseases is:

Time-consuming
Error-prone
Not scalable for large farms

LeafD solves this problem by automating disease detection using AI.

🎯 Objectives
Build an automated plant disease detection system
Apply transfer learning for efficient model training
Improve classification accuracy using deep learning
Create a scalable solution for real-world agricultural use
🛠️ Technologies Used
💻 Programming & Tools
Python
Google Colab / Jupyter Notebook
🤖 Machine Learning / Deep Learning
TensorFlow
Keras
Transfer Learning (EfficientNetB4)
📊 Libraries
NumPy
Matplotlib
Split-folders (dataset splitting)
📂 Dataset Details
Dataset: Plant Leaf Diseases Dataset (Augmented)
Size: ~900MB
Contains:
Multiple plant species
Healthy and diseased leaf images
📊 Data Split
Training: 80%
Validation: 10%
Testing: 10%
⚙️ System Workflow
🔹 Step 1: Data Preprocessing
Dataset split using splitfolders library
Images resized to 160x160
Batch processing for efficient training
🔹 Step 2: Model Architecture

Base Model:

EfficientNetB4 (Pretrained on ImageNet)

Custom Layers Added:

Global Average Pooling
Batch Normalization
Dense Layer (ReLU Activation)
Dropout Layer (0.5)
Output Layer (Softmax)
🔹 Step 3: Model Training
Optimizer: Adam
Loss Function: Sparse Categorical Crossentropy
Metrics: Accuracy
Batch Size: 32
🔹 Step 4: Model Evaluation
Tested on unseen dataset
Predictions compared with actual labels
Visualization using matplotlib
📊 Results & Performance
Achieved strong classification accuracy on validation data
Efficient training due to transfer learning
Successfully classified multiple disease categories
📸 Output Visualization
Grid-based visualization of predictions
Displays predicted vs actual labels
💡 Key Features
End-to-end ML pipeline
Transfer learning implementation
Automated dataset splitting
Visualization of predictions
Scalable deep learning architecture
🚀 Future Enhancements
Deploy as a web application using Streamlit
Add real-time image upload feature
Fine-tune model for higher accuracy
Integrate with mobile applications
Add disease treatment suggestions
📁 Project Structure
LeafD/
│── dataset/
│   ├── train/
│   ├── val/
│   ├── test/
│
│── LeafD_Model.ipynb
│── README.md
🧠 Skills Demonstrated
Technical Skills
Deep Learning (CNN)
Transfer Learning (EfficientNetB4)
Image Classification
TensorFlow / Keras
Practical Skills
Data preprocessing & handling large datasets
Model building & evaluation
Visualization & debugging
End-to-end ML pipeline development
👨‍💻 Author

Shubhanshu Kumar
Aspiring Data Analyst | Future Data Scientist

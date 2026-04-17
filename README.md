Leaf Disease Prediction using Machine Learning
📌 Overview

This project focuses on detecting plant leaf diseases using a Convolutional Neural Network (CNN). It classifies leaf images into categories such as Healthy, Early Blight, and Late Blight.

The system includes:

Data preprocessing & augmentation
Model training using deep learning
Evaluation & visualization
Real-time prediction via a web application
🚀 Features
🌱 Image classification using CNN
📊 Data preprocessing and augmentation
⚡ Fast and accurate predictions
🌐 Streamlit web app for real-time use
📈 Training & validation accuracy visualization
📂 Project Structure
leaf-disease-prediction-ml/
│
├── dataset/
│   ├── healthy/
│   ├── early_blight/
│   └── late_blight/
│
├── model/
│   └── leaf_disease_model.h5
│
├── app/
│   └── app.py
│
├── src/
│   ├── train.py
│   ├── predict.py
│   └── preprocess.py
│
├── notebook/
│   └── leaf_disease_training.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
📊 Dataset

This project uses a dataset inspired by the
PlantVillage Dataset, which contains thousands of labeled plant leaf images.

Classes:
Healthy
Early Blight
Late Blight
🛠️ Tech Stack
Python
TensorFlow / Keras
OpenCV
NumPy & Matplotlib
Streamlit
⚙️ Installation
git clone https://github.com/your-username/leaf-disease-prediction-ml.git
cd leaf-disease-prediction-ml
pip install -r requirements.txt
▶️ Training the Model
python src/train.py
🔍 Running Prediction
python src/predict.py
🌐 Run Web Application
streamlit run app/app.py
📈 Results
Achieved high accuracy on validation dataset
Efficient classification of plant diseases
Real-time prediction via web interface
📸 Screenshots (Add Your Images Here)
![App Screenshot](images/app.png)
![Accuracy Graph](images/accuracy.png)
🔮 Future Improvements
🚀 Implement Transfer Learning (ResNet50, MobileNet)
☁️ Deploy on cloud (AWS / Render / Heroku)
🌍 Expand dataset for more crops and diseases
📱 Build mobile application
👨‍💻 Author

Shubhanshu Kumar

🎓 BS CSDA, IIT Patna
📊 Aspiring Data Scientist & Data Analyst
🏷️ Tags

machine-learning deep-learning cnn image-classification tensorflow opencv streamlit data-science

⭐ Support

If you like this project, give it a ⭐ on GitHub!

🔥 Pro Tip (Important)

Before uploading:

Add screenshots
Upload model file carefully (or ignore if large)
Add .gitignore (ignore dataset & model if heavy)

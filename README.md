# 🌿 Leaf Disease Prediction using Machine Learning (LeafD)

## 📌 Project Overview

This project focuses on detecting and classifying plant leaf diseases using Machine Learning and Deep Learning techniques. The model is trained on a large dataset of plant leaf images (including tomato leaves) to identify various diseases and healthy conditions.

The main objective is to help farmers and researchers detect plant diseases early and take preventive measures to improve crop yield and quality.

---

## 📂 Dataset

* Dataset downloaded from Mendeley Data
* Size: ~905 MB
* Contains:

  * Thousands of plant leaf images
  * Multiple disease categories
  * Augmented images for better accuracy

### Dataset Structure

```
Plant_leave_diseases_dataset_with_augmentation/
│
├── Tomato___Healthy/
├── Tomato___Early_blight/
├── Tomato___Late_blight/
├── Tomato___Leaf_Mold/
├── Tomato___Tomato_Yellow_Leaf_Curl_Virus/
└── ...
```

---

## ⚙️ Technologies Used

* Python 🐍
* TensorFlow / Keras 🤖
* NumPy & Pandas 📊
* Matplotlib 📈
* OpenCV 🖼️
* Jupyter Notebook

---

## 🚀 Features

* Image-based plant disease detection
* Deep learning model using CNN
* Data preprocessing and augmentation
* High accuracy classification
* Scalable to multiple crops

---

## 🧠 Model Workflow

1. **Data Collection**

   * Dataset downloaded and extracted

2. **Data Preprocessing**

   * Image resizing and normalization
   * Train-test splitting

3. **Model Building**

   * Convolutional Neural Network (CNN)
   * Feature extraction layers

4. **Training**

   * Model trained on multiple epochs
   * Accuracy and loss monitored

5. **Evaluation**

   * Validation accuracy checked
   * Performance analysis

---

## 💻 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/leafd-disease-prediction.git
cd leafd-disease-prediction
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Download Dataset

```bash
wget -O dataset.zip "https://data.mendeley.com/public-files/datasets/..."
unzip dataset.zip
```

### 4️⃣ Run the Project

```bash
jupyter notebook
```

---

## 📊 Results

* Achieved high accuracy in disease classification
* Effective performance on augmented dataset
* Reliable detection across multiple disease classes

---

## 🔮 Future Improvements

* Web app deployment using Streamlit
* Real-time disease detection
* Expansion to more plant species
* Mobile app integration

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👩‍💻 Author

**Priya Kumari**

* B.Tech CSE (Data Science) Student
* Passionate about Machine Learning & Data Science

---

## ⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub!

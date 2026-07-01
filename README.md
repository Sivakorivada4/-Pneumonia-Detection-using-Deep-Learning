# 🩺 Pneumonia Detection using Deep Learning

## 📌 Overview

This project uses **Deep Learning** and **Transfer Learning** to detect **Pneumonia** from Chest X-ray images. A pre-trained **MobileNetV2** model is fine-tuned to classify X-ray images into two categories:

* 🟢 Normal
* 🔴 Pneumonia

The project demonstrates how Convolutional Neural Networks (CNNs) and transfer learning can be applied to medical image classification.

---

## 🎯 Objectives

* Build an accurate deep learning model for pneumonia detection.
* Apply image preprocessing and data augmentation.
* Use transfer learning to improve performance.
* Evaluate the model using multiple performance metrics.
* Predict pneumonia from unseen chest X-ray images.

---

## 📂 Dataset

**Dataset:** Chest X-ray Images (Pneumonia)

The dataset contains chest X-ray images divided into:

* Train
* Validation
* Test

Classes:

* Normal
* Pneumonia

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* MobileNetV2
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab

---

## 📁 Project Structure

```text
Pneumonia-Detection/
│
├── dataset/
│
├── notebook/
│   └── Pneumonia_Detection.ipynb
│
├── model/
│   └── pneumonia_model.keras
│
├── images/
│   ├── training_accuracy.png
│   ├── confusion_matrix.png
│   └── prediction.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## ⚙️ Workflow

1. Load the Chest X-ray dataset.
2. Preprocess and normalize images.
3. Apply image augmentation.
4. Load the pre-trained MobileNetV2 model.
5. Add custom classification layers.
6. Train the model.
7. Evaluate model performance.
8. Predict pneumonia on unseen images.

---

## 📊 Model Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Training & Validation Loss
* Training & Validation Accuracy

---

## 🚀 Results

* Successfully classified chest X-ray images into **Normal** and **Pneumonia**.
* Achieved strong validation performance using transfer learning.
* Reduced training time by leveraging MobileNetV2.
* Demonstrated the effectiveness of deep learning for medical image classification.

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Pneumonia-Detection.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

or open the notebook in **Google Colab**.

---

## 📷 Sample Outputs

Include screenshots such as:

* Dataset Samples
* Training Accuracy & Loss Graphs
* Confusion Matrix
* Classification Report
* Prediction Results

---

## 🔮 Future Improvements

* Deploy the model using Streamlit.
* Train with EfficientNet or Vision Transformer.
* Add Grad-CAM for model explainability.
* Extend to multi-class lung disease classification.
* Optimize for mobile deployment using TensorFlow Lite.

---

## 📚 Skills Demonstrated

* Deep Learning
* Computer Vision
* Transfer Learning
* Medical Image Classification
* TensorFlow & Keras
* Data Preprocessing
* Model Evaluation
* Image Augmentation

---

## 👨‍💻 Author

**Siva Korivada**

Aspiring AI/ML Engineer | Data Scientist

* GitHub: https://github.com/Sivakorivada4
---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

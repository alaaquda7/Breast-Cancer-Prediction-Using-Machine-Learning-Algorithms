# 🩺 Breast-Cancer-Prediction-Using-Machine-Learning-Algorithms

📌 Overview
This project applies deep learning to breast cancer detection using MRI scans.
It evaluates ResNet-50 v2, Vision Transformers (ViT), and Kolmogorov–Arnold Networks (KAN), and explores Hybrid models (ResNet+KAN, ViT+KAN) to deliver accurate, interpretable, and scalable AI support for diagnosis.

🎯 Objectives

•	🚀 Develop accurate deep learning models for medical image classification.

•	🔍 Compare different architectures (ResNet, ViT, KAN).

•	⚡ Explore fusion with KAN to enhance explainability and performance.

🛠️ Models Used

•	ResNet-50: CNN-based model for feature extraction.

•	Vision Transformer (ViT): Transformer-based architecture for image classification.

•	Kolmogorov-Arnold Networks (KAN): Spline-based model focusing on interpretability.

•	Hybrid Models (ResNet+KAN, ViT+KAN): Combines strengths of both paradigms.

📊 Results

•	ResNet-50 + KAN: 63% Accuracy

•	ViT + KAN: 93.10% Accuracy

• ViT : 87.75% Accuracy

•	✅ Hybrid models improved interpretability and overall performance.

Visual Results:

📈 Accuracy :

![ResNet+KAN Accuracy](resnet_kan_accuracy.png.png)
![ViT Accuracy](vit_accuracy.png.png)
![ViT+KAN Accuracy](vit_kan_accuracy.png.png)



🧮 Confusion Matrices
![ResNet+KAN Confusion Matrix](resnet_kan_confusion_matrix.png.png)
![ViT Confusion Matrix](vit_confusion_matrix.png.png)
![ViT+KAN Confusion Matrix](vit_kan_confusion_matrix.png.png)



📊 Classification Report
![ResNet+KAN Classification Report](resnet_kan_classification_report.png.png)
![ViT Classification Report](vit_classification_report.png.png)
![ViT+KAN Classification Report](vit_kan_classification_report.png.png)




📚 Dataset

A dataset containing 1,480 MRI images of breast cancer patients, classified into two categories: "healthy" and "diseased" (benign and malignant).

This dataset includes 40 images per category.

You can access the dataset here:

🔗 Breast Cancer Patients MRIs - Kaggle : https://www.kaggle.com/datasets/uzairkhan45/breast-cancer-patients-mris?

⚠️ Please note that the raw data is not uploaded to GitHub due to size and privacy restrictions.

⚙️ Installation

•	Clone the repository:

git clone https://github.com/username/breast-cancer-detection.git

cd breast-cancer-detection

•	Install dependencies:

pip install -r requirements.txt

▶️ Usage

Example training commands:

python vit_kan.py

python resnet_kan.py



👨‍💻 Team

•	Alaa Qudah

•	Dana Freihat

•	Layan Al-Hiassat

•	Mai Al-Omari


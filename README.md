# Breast-Cancer-Prediction-Using-Machine-Learning-Algorithms

## Overview: 
This project applies deep learning to breast cancer detection using MRI scans.   It evaluates  ResNet-50 v2, Vision Transformers (ViT), and Kolmogorov–Arnold Networks (KAN) , and explores  Hybrid models (ResNet+KAN, ViT+KAN) to deliver accurate, interpretable, and scalable AI support for diagnosis.  

## Objectives :
Develop accurate deep learning models for medical image classification.
Compare different architectures (ResNet, ViT, KAN).
Explore fusion with KAN to enhance explainability and performance.

## Models Used:
ResNet-50: A powerful CNN-based model for feature extraction.
Vision Transformer (ViT): A transformer-based architecture for image classification.
Kolmogorov-Arnold Networks (KAN): A novel spline-based model focusing on interpretability.
Hybrid Models (ResNet+KAN, ViT+KAN): To combine strengths of both paradigms.

## Results: 
ResNet-50 + KAN: 63% Accuracy
ViT + KAN: 93.10% Accuracy
Hybrid models improved interpretability and overall performance.
Graphs, confusion matrices, and comparison tables are available in the results/ folder.

## Dataset:
A dataset containing 1,480 MRI images of breast cancer patients, classified into two categories: "healthy" and "diseased" (benign and malignant), was used for testing. This dataset includes 40 images per category.
You can access the dataset via the following link:
🔗 Breast Cancer Patients MRIs - Kaggle : https://www.kaggle.com/datasets/uzairkhan45/breast-cancer-patients-mris?
Please note that the raw data is not uploaded to GitHub due to its large size and privacy restrictions.

## Installation :
- Clone the repository:
git clone https://github.com/username/breast-cancer-detection.git
cd breast-cancer-detection
- Install dependencies: pip install -r requirements.txt

## Usage:
Example training commands :
python vit_kan.py
python resnet_kan.py

## Project Structure: 
├── vit_kan.py             # Training and inference for Vision Transformer + KAN
├── resnet_kan.py          # Training and inference for ResNet-50 + KAN
├── results/               # Folder containing results: accuracy curves, confusion matrices, tables, charts
├── documentation/         # Any project documentation, reports, or supplementary material
├── README.md              # Project description, usage, and details


## Team work: 
.Alaa Qudah
.Dana Freihat 
.Layan Al-Hiassat
.Mai Al-Omari

Al-Hiassat
.Mai Al-Omari

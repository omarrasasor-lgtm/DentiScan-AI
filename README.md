# DentiScan-AI
# 🦷 DentiScan AI — Dental Disease Diagnosis System

A deep learning-based AI model that diagnoses dental conditions from images, 
built as a graduation project at Istinye University (2025–2026).

## 👥 Team Members
- Omar Rasas
- Taleb jarrar 
- Esra 
## 🎯 What It Does
Upload a dental image and the model will classify it into one of 8 conditions:
- **Calculus** — tartar buildup
- **Caries** — tooth decay/cavities
- **Gingivitis** — gum inflammation
- **Mouth Ulcer**
- **Hypodontia** — missing teeth
- **Tooth Discoloration**
- **CANCER** — oral cancer warning
- **Healthy** — no issues detected

It also provides treatment recommendations and tips for each diagnosis.

## 🧠 Model Architecture
- **Base Model:** DenseNet121 (pretrained on ImageNet)
- **Technique:** Transfer Learning + Fine-tuning
- **Input Size:** 224×224 pixels
- **Output:** 8-class softmax classification
- **Final Accuracy:** ~81% on test data

## 📊 Dataset
- 8 dental condition categories
- 500 images per class (balanced via augmentation)
- Split: 80% train / 10% validation / 10% test
- Augmentation: rotation, zoom, horizontal flip, brightness variation

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- Google Colab
- scikit-learn (evaluation metrics)
- Matplotlib & Seaborn (visualization)

## 📁 Project Structure

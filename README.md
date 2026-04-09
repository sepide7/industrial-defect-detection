# 🔍 Industrial Defect Detection

This project presents a hybrid CNN + XGBoost model for classifying industrial surface defects.

## 🚀 Features
- EfficientNetB0 feature extraction
- XGBoost classifier
- 5-Fold Cross Validation
- Data Augmentation
- Class Imbalance Handling

## 📊 Results
- Accuracy: ~79%
- Macro F1: 0.76

## 🧠 Model Pipeline
CNN → Feature Extraction → XGBoost → Prediction

## ▶️ Run
```bash
python src/train.py
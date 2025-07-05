# 🧬 CNN Cancer Detection – Kaggle Mini Project

This repository contains my submission for the **Histopathologic Cancer Detection** challenge on Kaggle, completed as part of Week 3 of the Coursera "Introduction to Deep Learning" course (University of Colorado Boulder).

The goal is to classify **small histopathology image patches (96x96 pixels)** as either containing metastatic cancer or not (binary classification).

---

## 📁 Project Structure

- `cancer_detection.ipynb`: Jupyter notebook with full pipeline
- `submission.csv`: Prediction output file for Kaggle submission
- `leaderboard_screenshot.png`: Screenshot of final Kaggle score
- `README.md`: Project overview and structure

---

## 🧠 Model Summary

- **Architecture**: ResNet18 pretrained on ImageNet
- **Loss**: Binary Cross Entropy with Logits (`BCEWithLogitsLoss`)
- **Optimizer**: Adam (`lr=1e-4`)
- **Epochs**: 20
- **Validation Accuracy**: ~91.6%

---

## 🔍 Exploratory Data Analysis (EDA)

- Class imbalance visualization
- Sample images for both cancerous and non-cancerous tissue
- Check for missing values

---

## 📈 Training Results

- Plotted training/validation loss
- Validation accuracy curve
- Analysis of model performance and suggestions for improvements

---

## ✅ Deliverables

- **Jupyter Notebook**: Included here and submitted to Coursera
- **GitHub Repo**: [Link to this repo](https://github.com/yourusername/cnn-cancer-detection-kaggle)
- **Kaggle Leaderboard Screenshot**: Provided as `leaderboard_screenshot.png`

---

## 📌 Future Improvements

- Experiment with EfficientNet / MobileNet
- Use focal loss for class imbalance
- Implement k-fold cross-validation
- Add dropout or data augmentation

---

## 🏆 Kaggle Competition

> Challenge: [Histopathologic Cancer Detection](https://www.kaggle.com/competitions/histopathologic-cancer-detection)

---

Feel free to fork, star, or reach out with questions! 🤝

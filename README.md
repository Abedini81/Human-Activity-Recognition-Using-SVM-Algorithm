# Human Activity Recognition Using SVM Algorithm

This project implements a Support Vector Machine (SVM) algorithm to classify human physical activities based on smartphone sensor data. The dataset used is publicly available on Kaggle: [Human Activity Recognition with Smartphones](https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones), which contains time and frequency domain features extracted from accelerometer and gyroscope signals.

## 📊 Dataset Overview

The dataset includes data from 30 subjects performing six different activities:
- Walking  
- Walking Upstairs  
- Walking Downstairs  
- Sitting  
- Standing  
- Laying

## 🔍 Project Objectives

- Load and preprocess the HAR dataset
- Build an initial Support Vector Machine (SVM) model
- Evaluate performance using classification metrics and confusion matrix
- Apply hyperparameter tuning using GridSearchCV
- Analyze and interpret the final model’s performance

## 🛠️ Technologies Used

- Python  
- scikit-learn  
- pandas  
- matplotlib  
- seaborn  
- Jupyter Notebook

## 📁 Project Structure

├── SVM.ipynb # Main notebook containing all code and output ├── README.md # Project overview and usage instructions

## 📈 Evaluation Metrics

The model is evaluated using:
- **Classification Report**: Provides precision, recall, F1-score per class
- **Confusion Matrix**: Visualizes model predictions vs. actual labels

The final SVM model shows strong performance across most activity classes, with minor misclassifications between activities with similar motion patterns, such as sitting vs. standing.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Abedini81/Human-Activity-Recognition-Using-SVM-Algorithm.git
   cd Human-Activity-Recognition-Using-SVM-Algorithm
Open the notebook:

Use Jupyter Notebook or Jupyter Lab to run SVM.ipynb

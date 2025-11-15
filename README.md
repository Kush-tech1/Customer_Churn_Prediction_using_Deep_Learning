# 🧠 Bank Customer Churn Prediction (ANN)

## 📘 Overview
This project predicts whether a banking customer will **exit (churn)** using an Artificial Neural Network (ANN).  
The notebook covers end-to-end steps: data loading → cleaning → preprocessing → model training → evaluation.

## ⚙️ Workflow Summary
- Load dataset (`Churn_Modelling.csv`) and preview basic features  
- Drop non-essential columns (ID, name, geography, gender fields)  
- Scale numerical features using `StandardScaler`  
- Split data into train/test sets  
- Build ANN model using Keras (Dense layers with ReLU + Sigmoid output)  
- Train for 100 epochs with Adam optimizer  
- Evaluate performance on train and test sets  

## 📊 Model Performance
- **Test Accuracy:** ~86%  
- **Train Accuracy:** ~85.8%  
- Output generated through probability thresholding (`>0.5 → churn`)  

## 🛠 Tech Stack
- Python  
- pandas, numpy  
- scikit-learn  
- TensorFlow / Keras  
- Jupyter Notebook  

## 💡 Key Steps Covered in Notebook
- Data preprocessing & feature scaling  
- ANN architecture with multiple Dense layers  
- Model training with cross-entropy loss  
- Prediction thresholding  
- Accuracy evaluation  


# 🏥 DiaPredict-AI: Diabetes Risk Prediction using Deep Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Framework-orange?logo=pytorch)
![License](https://img.shields.io/badge/License-MIT-green)

DiaPredict-AI is a deep learning-based health utility designed to predict the risk of diabetes using patient health indicators. Built with **PyTorch**, this model analyzes 21 critical health features to provide a high-fidelity risk assessment.

---

## 🚀 Key Features
* **Neural Network Architecture:** Multi-layer Perceptron (MLP) for binary classification.
* **Large Scale Data:** Trained on 70,000+ records from the BRFSS 2015 dataset.
* **Optimized Preprocessing:** Uses Robust Scaling to handle medical data outliers.
* **Evaluation Metrics:** High focus on Precision and Recall for medical reliability.

---

## 📊 Project Workflow
Below is the architectural flow of the project from data ingestion to final prediction:

<img width="500" height="500" alt="Complete Model Workflow" src="https://github.com/user-attachments/assets/bdefaf92-944e-4d9c-aaa7-36379e9d12fc" />


### 1. Data Preparation
- Dataset: Kaggle (Diabetes Health Indicators).
- Handling Class Imbalance: 50-50 split for unbiased training.
- Scaling: `StandardScaler` for neural network compatibility.

### 2. Model Architecture
```python


# 3-Layer Neural Network
- Input Layer: 21 Features
- Hidden Layer 1: 128 Neurons (ReLU + Dropout)
- Hidden Layer 2: 64 Neurons (ReLU)
- Output Layer: 2 Neurons (Softmax for Classification)


3. Training & Performance
The model was trained for 100 epochs with an Adam optimizer.

Accuracy: ~75.14%

Evaluation: Confusion Matrix and Loss Curves included in the analysis.

📌 Future Scope
[.] Integration with a Flask/Streamlit Web Dashboard.

[.] Enhancing accuracy through Hyperparameter Tuning (Optuna).

[.] Mobile App development for real-time health monitoring.

Developed by Vinit Koshti B.Tech Student in CSE (AIML)

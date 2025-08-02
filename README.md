# 🚗 Accident Severity Prediction using Decision Tree

This project aims to simulate road accident data and build a machine learning model to predict accident severity based on environmental and situational factors.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Dataset Features](#dataset-features)
- [Technologies Used](#technologies-used)
- [Data Preprocessing](#data-preprocessing)
- [Model Training & Evaluation](#model-training--evaluation)
- [Visualizations](#visualizations)
- [How to Run](#how-to-run)
- [Future Improvements](#future-improvements)
- [Contact](#contact)

---

## 🧾 Overview

- Generates synthetic accident data (1000 samples)
- Applies data preprocessing (encoding, scaling)
- Trains a Decision Tree Classifier
- Evaluates performance with classification metrics
- Visualizes the decision tree and confusion matrix

---

## 📊 Dataset Features

| Feature           | Description                                        |
|------------------|----------------------------------------------------|
| `Hour`            | Hour of accident (0–23)                           |
| `Day_of_Week`     | Day of the week (0 = Monday, 6 = Sunday)          |
| `Weather`         | Weather condition: Clear, Rain, Fog, Snow         |
| `Road_Condition`  | Road condition: Dry, Wet, Icy                     |
| `Speed_Limit`     | Speed limit in km/h (30–120)                      |
| `Num_Vehicles`    | Number of vehicles involved (1–5)                 |
| `Severity`        | Target variable: Minor, Severe, Fatal             |

---

## ⚙️ Technologies Used

- **Programming Language**: Python  
- **Libraries**:
  - `pandas`, `numpy` – Data handling
  - `matplotlib`, `seaborn` – Visualization
  - `scikit-learn` – ML model, preprocessing, evaluation

---

## 🧹 Data Preprocessing

- Label Encoding for `Severity`
- One-Hot Encoding for `Weather`, `Road_Condition`
- Feature scaling using `StandardScaler`
- Train-Test Split: 80% train, 20% test

---

## 🤖 Model Training & Evaluation

- **Model**: Decision Tree Classifier (max_depth = 5)
- **Accuracy Score**
- **Classification Report** (Precision, Recall, F1)
- **Confusion Matrix**

---

## 📈 Visualizations

- Confusion Matrix (Seaborn heatmap)
- Decision Tree structure (colored and labeled)

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/accident-severity-prediction.git
   cd accident-severity-prediction

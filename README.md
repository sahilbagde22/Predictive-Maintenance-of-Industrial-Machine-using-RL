# Predictive Maintenance of Industrial Machines

## 📌 Overview
This project implements a **Predictive Maintenance** system for industrial machines using **Machine Learning** and **Reinforcement Learning** concepts.  
By leveraging historical sensor data, the model predicts potential equipment failures **before** they occur, allowing for timely maintenance, reduced downtime, and optimized operational costs.

## 📊 Dataset
- **Source:** `predictive_maintenance.csv`
- **Features:** Sensor readings, operational conditions, and maintenance history.
- **Target Variable:** Machine failure status (binary classification).
- **Preprocessing:**
  - Missing value handling
  - Feature scaling with `MinMaxScaler`
  - Resampling for class imbalance

## 🛠 Tech Stack
- **Programming Language:** Python
- **Libraries:**  
  - Data Processing: `pandas`, `numpy`  
  - Machine Learning: `scikit-learn`, `torch`  
  - Reinforcement Learning: `gym`  
  - Visualization: `matplotlib`

## ⚙ Methodology
1. **Data Loading & Exploration**
2. **Data Preprocessing**  
   - Feature scaling  
   - Class balancing using resampling  
3. **Model Building**
   - Custom Gym environment for predictive maintenance decision-making
   - ML classification models to predict failures
4. **Model Evaluation**
   - Classification Report (Precision, Recall, F1-score)
   - Confusion Matrix
5. **Visualization**
   - Performance metrics
   - Model training curves

## 📈 Results
- High recall for failure detection, ensuring minimal false negatives.
- Balanced precision-recall tradeoff to optimize maintenance cost vs. downtime.


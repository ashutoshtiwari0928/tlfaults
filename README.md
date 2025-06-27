# ⚡ Machine Learning-Based Fault Detection in Transmission Lines

This project uses machine learning techniques to automatically detect and classify faults in electrical power transmission lines based on real-time voltage and current data.

---

## 📌 Objective

To develop an intelligent system that:
- Detects faults in transmission lines.
- Classifies the fault type (e.g., LG, LLG, LLL, LLG, etc.).
- Identifies the fault location in the transmission network.

---

## 🔧 Features

- Supervised machine learning model trained on voltage and current data.
- Predicts both **fault type** and **fault location**.
- Can be adapted to various power system test cases (e.g., IEEE 5-bus system).
- Compatible with real-time data input from sensors or simulators.

---

## 🧠 Technologies Used

- **Python** 🐍
- **Scikit-learn** for ML models
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for visualization
- **Jupyter Notebook** for experimentation
- **MATLAB / PSCAD / Simulink** (optional, for data simulation)

---

## 📁 Dataset

- Simulated data from the IEEE 5-bus system
- Includes:
  - Phase voltages and currents
  - Fault type labels
  - Fault locations

---

## 📊 Model Overview

- **Input**: Voltage and current values at each bus/branch
- **Output**:
  - Fault type (Multiclass classification)
  - Fault location (Regression or classification)

Trained using:
- Random Forest
- Decision Trees
- SVM
- ANN (optional, for more advanced accuracy)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fault-detection-transmission-lines.git
   cd fault-detection-transmission-lines

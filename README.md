# Electronic Circuit Fault Detection Using Machine Learning Classification Models

## Project Overview

This project focuses on detecting faults in electronic circuits using Machine Learning classification techniques. Electrical parameters such as Voltage, Current, Resistance, Temperature, Power, and Frequency are used to determine whether a circuit is operating normally or experiencing a fault.

The project compares the performance of three machine learning models:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier (Ensemble Model)

The models are evaluated using Accuracy, Precision, Recall, and F1-Score metrics.

---

## Problem Statement

Electronic circuits may experience faults due to abnormal operating conditions such as overheating, excessive current flow, voltage fluctuations, and frequency instability.

The objective of this project is to develop a machine learning-based system that can automatically classify a circuit as:

- Normal Circuit (0)
- Faulty Circuit (1)

based on electrical operating parameters.

---

## Dataset Description

The dataset contains the following features:

- Voltage
- Current
- Resistance
- Temperature
- Power
- Frequency

Target Variable:

- Fault
  - 0 → Normal Circuit
  - 1 → Fault Detected

The dataset was synthetically generated using realistic electrical operating ranges and fault conditions commonly observed in electronic systems.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Machine Learning Models

### 1. Logistic Regression
Used as the baseline classification model for binary fault detection.

### 2. Decision Tree Classifier
Used to identify fault patterns through decision-based classification.

### 3. Random Forest Classifier
Used as the ensemble learning model to improve prediction accuracy and reduce overfitting.

---

## Performance Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

---

## Project Workflow

1. Load Dataset
2. Data Preprocessing
3. Train-Test Split
4. Model Training
5. Model Testing
6. Performance Evaluation
7. Results Comparison
8. Graph Generation

---

## Results

The Random Forest Classifier achieved the best overall performance among all implemented models due to ensemble learning and improved generalization capability.

---

## Future Scope

- Real-time fault monitoring
- IoT-based fault detection systems
- Deep Learning models
- Cloud-based monitoring platforms
- Integration with industrial electronic systems

---

## Author

Name: Vaibhav Balaji

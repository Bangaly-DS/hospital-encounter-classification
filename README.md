# 🏥 Hospital Patient Encounter Classification

This project uses hospital patient records to classify healthcare encounters (inpatient, outpatient, emergency, etc.) using machine learning.

## 🔍 Overview

- **Goal:** Predict the `ENCOUNTERCLASS` using structured data from electronic health records.
- **Model:** Random Forest Classifier
- **Accuracy:** 100% on test data (requires further validation for real-world deployment)

## 🧠 Key Steps

- Cleaned and explored hospital encounter data
- Handled missing values, converted datetime fields, and created new features
- Encoded categorical variables and scaled numerical data
- Trained a Random Forest model to classify encounter types
- Evaluated using classification report and confusion matrix

## 📊 Technologies Used

- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/hospital-encounter-classification.git
   cd hospital-encounter-classification

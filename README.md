# BI Final Project – Tel-Hai College

## 📄 Overview
This repository contains the final project for the **Business Intelligence** course at Tel-Hai College (Spring Semester 2025).  
The project applies **Classification**, **Clustering**, and **Association Rule Mining** techniques to three datasets, demonstrating data preprocessing, model building, and interpretation of results using Python.

---

## 📊 Project Parts

### 1. Classification – Heart Disease Risk Prediction
**Dataset:** `framingham.csv`  
- Used **Random Forest** to identify the most important features predicting 10-year CHD risk.  
- Built a **Decision Tree Classifier** with a 70/30 train-test split.  
- Calculated **Accuracy**, **Precision**, and **Recall**.  
- Discussed advantages of Decision Trees and strategies to prevent overfitting.

### 2. Clustering – Patient Triage
**Dataset:** `patient_dataset.csv`  
- Applied **Elbow Method** to determine the optimal number of clusters.  
- Performed **K-Means Clustering** to group patients based on symptoms.  
- Discussed limitations of K-Means in a medical triage context.

### 3. Association Rules – Market Basket Analysis
**Dataset:** `GroceryDataset.csv`  
- Implemented the **Apriori Algorithm** to discover frequent itemsets.  
- Generated rules with minimum support of 50% and confidence of 70%.  
- Interpreted a sample rule and proposed real-world retail applications.

---

## 📂 Repository Structure
```
BI-Final-Assignment-TelHai/
│
├── classification_analysis.ipynb   # Main analysis notebook
├── framingham.csv                   # Classification dataset
├── patient_dataset.csv               # Clustering dataset
├── GroceryDataset.csv                # Association dataset
└── Final_HW-Tel-Hai.pdf              # Original assignment questions provided by the lecturer
```

---

## 🛠 Requirements
- Python 3.9+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- mlxtend

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn mlxtend
```

---

## ▶️ How to Run
1. Clone this repository:
```bash
git clone https://github.com/your-username/BI-Final-Assignment-TelHai.git
cd BI-Final-Assignment-TelHai
```
2. Install the required packages:
```bash
pip install -r requirements.txt
```
3. Open and run the Jupyter Notebook:
```bash
jupyter notebook classification_analysis.ipynb
```

---

## 📌 Author
**Daniel Bonder**  
Tel-Hai College – Business Intelligence Final Project (2025)

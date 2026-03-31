# 🫀 Heart Attack Risk Factor Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Domain](https://img.shields.io/badge/Domain-Healthcare-red)
![ML](https://img.shields.io/badge/ML-Logistic%20Regression-orange)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** and applies
**Machine Learning** on clinical heart attack data to identify key risk
factors responsible for heart attacks in patients.

---

## 📊 Dataset Description
| Feature | Description |
|---------|-------------|
| age | Age of the patient |
| sex | Gender (1 = Male, 0 = Female) |
| cp | Chest pain type (0–3) |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol (mg/dl) |
| fbs | Fasting blood sugar > 120 mg/dl |
| restecg | Resting ECG results |
| thalach | Maximum heart rate achieved |
| exang | Exercise induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels |
| thal | Thalassemia type |
| **target** | **1 = Heart Attack, 0 = No Heart Attack** |

- **Total Records:** 303
- **Total Features:** 14

---

## 🔍 Project Workflow
```
1. Data Loading & Inspection
2. Handling Missing Values & Duplicates
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Building (Logistic Regression)
6. Model Evaluation
```

---

## 📈 Model Performance
| Metric | Score |
|--------|-------|
| ✅ Accuracy | **81.3%** |
| 🎯 Precision | 0.81 |
| 🔁 Recall | 0.81 |
| 📊 F1-Score | 0.81 |

---

## 🛠️ Tech Stack
- **Language:** Python 3.10
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Tool:** Jupyter Notebook

---

## 🚀 How to Run
```bash
# 1. Clone the repository
git clone https://github.com/TusharParihar128/Heart-attack-EDA-and-ML-analysis.git

# 2. Go to the folder
cd Heart-attack-EDA-and-ML-analysis

# 3. Install libraries
pip install -r requirements.txt

# 4. Open the notebook
jupyter notebook
```

---

## 📁 Project Structure
```
Heart-attack-EDA-and-ML-analysis/
│
├── Examining_factors_responsible_for_Heart_Attack.ipynb
├── data.xlsx
├── requirements.txt
└── README.md
```

---
## 👤 Author
**Tushar Parihar**
- GitHub: [@TusharParihar128](https://github.com/TusharParihar128)
- 🎓 This project was completed as part of my Data Analysis Capstone Project at **Simplilearn Platform**

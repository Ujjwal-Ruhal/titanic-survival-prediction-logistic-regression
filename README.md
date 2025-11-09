# Titanic Survival Prediction (Logistic Regression)

This project predicts whether a passenger survived the Titanic disaster using a Logistic Regression model. The goal is to understand how factors like gender, passenger class, and age influenced survival outcomes.

---

## Dataset
- Source: Kaggle Titanic Dataset  
- Columns such as **Name**, **Ticket**, and **Cabin** were dropped as they do not contribute effectively to prediction.

---

## Feature Engineering
- Encoded the **Sex** column (male/female → numeric)
- Dropped irrelevant columns (**Name**, **Ticket**, **Cabin**)
- Handled missing values where necessary

---

## Model Used
- **Logistic Regression** from `sklearn.linear_model`

---

## Accuracy
| Dataset | Accuracy |
|--------|----------|
| Test Set | **0.7482** |

This score is average, which is expected for baseline Logistic Regression without aggressive feature engineering. Improvement is possible using:
- More features (family size, title extraction, etc.)
- Better models (Random Forest, XGBoost)

---

## Environment
- Developed in **Kaggle Notebook**

---

## Files Included
| File | Description |
|------|-------------|
| `titanic_survival_prediction.ipynb` | Main notebook containing training & evaluation |

---

## How to Run
1. Download the notebook and dataset
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn

# Heart-Disease-Prediction-
Predicts the likelihood of heart disease using clinical data and a Logistic Regression model. Includes data preprocessing, training, testing, and accuracy evaluation. 


# Heart Disease Prediction using Logistic Regression

## Objective
To predict the likelihood of heart disease in a patient using clinical features such as age, cholesterol level, resting blood pressure, and other medical parameters. This model supports early risk assessment and decision-making in healthcare settings.


## Dataset Overview
- **Source**: UCI Heart Disease Dataset  
- **Instances**: 303 patient records  
- **Features**: 13 clinical attributes  
- **Target**:  
  - `0` → No Heart Disease  
  - `1` → Presence of Heart Disease  

---

## Features Used
- `age` – Patient’s age  
- `sex` – Gender  
- `cp` – Chest pain type  
- `trestbps` – Resting blood pressure  
- `chol` – Serum cholesterol  
- `fbs` – Fasting blood sugar  
- `restecg` – Resting ECG results  
- `thalach` – Maximum heart rate  
- `exang` – Exercise-induced angina  
- `oldpeak` – ST depression  
- `slope` – Slope of the ST segment  
- `ca` – Number of major vessels colored  
- `thal` – Thalassemia  

---

## Tools & Libraries
- **Language**: Python  
- **Libraries**: `pandas`, `numpy`, `scikit-learn`

---

## Project Workflow
1. **Data Loading & Cleaning**  
2. **Exploratory Data Analysis (EDA)**  
3. **Feature and Target Separation**  
4. **Train-Test Split** (80/20 with stratification)  
5. **Model Training** using **Logistic Regression**  
6. **Model Evaluation** with **accuracy score**  
7. **Predictive System** for new patient input

---

## Model Performance
- **Training Accuracy**: _86.07%_  
- **Testing Accuracy**: _81.97%_  

---

##Sample Prediction Output
```python
input_data = (62,0,0,140,268,0,0,160,0,3.6,0,2,2)
# Output: The person has Heart Disease

# 🫀 Heart Attack Prediction in Indonesia

Using data-driven modeling to support early detection and prevention of cardiovascular disease in Indonesia.

---

## 📌 Overview

Cardiovascular disease remains a top cause of mortality worldwide, and Indonesia is experiencing a rising burden. Many cases go undiagnosed or are detected too late due to gaps in healthcare access and early warning systems. This project leverages machine learning to predict heart attack risk based on clinical, demographic, and lifestyle features.

---

## 📂 Dataset

- **Source**: [Kaggle - Heart Attack Prediction in Indonesia](https://www.kaggle.com/datasets/ankushpanday2/heart-attack-prediction-in-indonesia)
- **Records**: Real-world patient data
- **Features**: 25+ features including:
  - **Demographic**: `age`, `gender`, `region`, `income_level`
  - **Clinical**: `blood_pressure`, `cholesterol`, `diabetes`, `hypertension`, `previous_heart_disease`, etc.
  - **Lifestyle**: `smoking_status`, `alcohol_consumption`, `physical_activity`, `dietary_habits`, `sleep_hours`
- **Target**: `heart_attack` (0 = No, 1 = Yes)

---

## 🧪 Project Objectives

- Identify key risk indicators for heart attacks in the Indonesian population
- Train a machine learning model to predict heart attack likelihood
- Provide actionable insights to support early intervention and public health strategies

---

## 📊 Exploratory Data Analysis (EDA)

Key findings:

- **Hypertension**, **diabetes**, and **previous heart disease** are significantly more common in patients who experienced heart attacks
- **Smoking status** is a critical lifestyle factor strongly associated with risk

---

## 🤖 Model: Random Forest Classifier

- **Model**: `RandomForestClassifier` (from `scikit-learn`)
- **Rationale**:
  - Effective for handling tabular health data
  - Provides feature importance metrics
  - Handles non-linear relationships and mixed feature types

### 🔍 Top Features Identified:

- `previous_heart_disease`
- `hypertension`
- `diabetes`
- `smoking_status`

These features showed both statistical significance in EDA and high importance in the model.

---

## 📝 Insights & Recommendations

### ✅ Key Risk Indicators:
- History of heart disease
- Hypertension
- Diabetes
- Smoking behavior

### 🧑‍⚕️ Public Health Impact:
- These factors are relatively easy to identify in clinical and community health settings
- Early detection can be feasible even in rural or under-resourced areas

### 🛠️ Clinical & Policy Application:
- Incorporate predictive features into routine screenings
- Develop lightweight mobile or web-based apps for pre-screening
- Use data to inform public awareness campaigns and targeted prevention

---

## 🚀 Next Steps

- Expand data collection, especially from rural areas
- Validate model on a broader and more recent population
- Collaborate with health organizations in Indonesia for real-world integration

---

## 📦 Requirements

- Python ≥ 3.8  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- jupyter (optional, for notebook analysis)

---

## 📬 Contact

For questions or collaboration, feel free to reach out via [GitHub Issues](https://github.com/keithhauzh/HEART-ATTACK-PREDICTION-MODEL/issues).

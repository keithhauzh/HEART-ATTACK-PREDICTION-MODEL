# ❤️ Heart Attack Risk Prediction – Indonesia

## Overview  
This project leverages clinical and lifestyle health data to predict the risk of heart attacks. Given Indonesia's growing burden of cardiovascular disease, the aim is to support early detection and prevention through data-driven methods — especially in rural and underserved communities.

---

## 🔍 Problem Statement  
Cardiovascular disease is the leading cause of death worldwide. In Indonesia, delayed diagnosis and limited access to preventative healthcare result in many heart attacks being caught too late. Early intervention tools based on real data can help bridge this gap.

---

## 🎯 Objectives  
- Identify key risk factors contributing to heart attacks  
- Train a machine learning model to predict heart attack risk  
- Provide insights to support public health programs and screening efforts

---

## 📦 Dataset  
- **Source:** Synthetic or adapted data representing Indonesian patient contexts  
- **Size:** (Insert number of records and features)  
- **Target:** `heart_attack` (Binary: 0 = No, 1 = Yes)

### Feature Categories:
- **Demographic:** `age`, `gender`, `region`, `income_level`  
- **Clinical:** `hypertension`, `diabetes`, `blood_pressure`, `cholesterol`, `obesity`, etc.  
- **Lifestyle:** `smoking_status`, `alcohol_consumption`, `physical_activity`, `stress_level`, `sleep_hours`, etc.

---

## 📊 Exploratory Data Analysis (EDA)  
- **Age**, **hypertension**, and **cholesterol** show higher values among those with heart attacks  
- **Smoking** and **EKG abnormalities** are more common in positive cases  
- A correlation heatmap shows strong associations between chronic conditions and heart attack risk

---

## 🤖 Model: Random Forest Classifier  
- A `RandomForestClassifier` was trained to predict heart attack risk  
- Feature importance indicates the most predictive variables:

  **Top 5 Risk Indicators:**  
  - `previous_heart_disease`  
  - `hypertension`  
  - `smoking_status`  
  - `diabetes`  
  - `obesity`

- Performance metrics (accuracy, precision, recall) were used to evaluate effectiveness

---

## 📝 Insights & Recommendations

### Public Health Impact  
- **High-risk groups:** Older adults with existing chronic conditions and poor lifestyle habits  
- **Early detection feasibility:** Many risk factors (e.g., BP, waist size, smoking status) are measurable in basic clinical settings  
- **Applicability in rural clinics:** Minimal tech required for screening key variables

### Policy & Clinical Use  
- Potential integration into community health screening or mobile health apps  
- Emphasizes low-cost, data-based prevention for scalable impact

---

## 🚀 Next Steps  
- Expand dataset with local Indonesian health records  
- Incorporate geographic, behavioral, or environmental variables  
- Collaborate with public health officials to deploy tools in real-world settings

---

## 🧠 Goal  
Enable earlier, more accessible detection of heart attack risk using machine learning — empowering health systems to act before it’s too late.

---


# 🏥 ICU Patient Survival Prediction

## 🧾 Project Summary

This project builds a complete machine learning pipeline to predict patient survival after admission to an Intensive Care Unit (ICU). Using real-world hospital data, we apply preprocessing techniques, handle imbalanced classes, train multiple classifiers, and apply SHAP explainability to interpret the results.

This simulation demonstrates how interpretable AI can assist in clinical decision support and aligns with data analyst and system control roles in domains where prediction accuracy and transparency are critical.

---

## 🎯 Objectives

- Predict ICU patient mortality using tabular clinical data  
- Build a full end-to-end machine learning pipeline  
- Handle class imbalance using SMOTE  
- Compare multiple classifiers and evaluate model performance  
- Use SHAP to interpret feature importance in predictions  

---

## 📁 Dataset

**Source:** ICU Mortality Dataset (University Assignment – anonymized)  
- ~90,000 patient records  
- Features: Demographic data, lab test results, treatment indicators  
- Target: `Survived` (0 = died, 1 = survived)  
- *Due to privacy, only synthetic or summarized data are shared here*

---

## 🧠 Skills Demonstrated

| Category             | Skills & Tools |
|----------------------|----------------|
| Preprocessing        | Missing value handling, encoding, standard scaling |
| Class Balancing      | SMOTE (Synthetic Minority Over-sampling Technique) |
| Modeling             | Logistic Regression, XGBoost, LightGBM |
| Evaluation           | Accuracy, Precision, Recall, F1-score, ROC AUC |
| Explainability       | SHAP (TreeExplainer, summary & force plots) |
| Tools                | Python, scikit-learn, imbalanced-learn, matplotlib, SHAP |

---

## 🛠️ Folder Structure

ICU-Patient-Survival-Prediction/
├── data/
│ └── sample_data.csv
├── notebooks/
│ └── survival_modeling.ipynb
├── src/
│ ├── preprocess.py
│ └── model_pipeline.py
├── img/
│ ├── shap_summary_plot.png
│ └── roc_auc_curve.png
├── reports/
│ └── survival_analysis_summary.pdf
└── README.md

yaml
Sao chép
Chỉnh sửa

---

## 📊 Key Analyses & Results

- **Class Imbalance:** The dataset was highly imbalanced (Survived: 82% / Died: 18%). SMOTE was used to improve model learning on minority class.  
- **Model Performance:**  
  - Logistic Regression: ROC AUC = 0.78  
  - XGBoost: ROC AUC = 0.86  
  - LightGBM: ROC AUC = **0.87**  
- **SHAP Analysis:** Top features impacting mortality include `creatinine`, `age`, `vasopressor use`, and `blood pressure`

---

## 🧩 Use Cases

| Stakeholder        | Use |
|--------------------|-----|
| ICU Doctors        | Predict patient risk and allocate resources earlier |
| Hospital Analysts  | Understand mortality drivers for quality improvement |
| Medical AI Teams   | Build interpretable models with explainability built-in |
| Health System Ops  | Plan interventions for high-risk groups |

---

## 💡 Visual Highlights

> ![SHAP Summary Plot](img/shap_summary_plot.png)  
> ![ROC AUC Curve](img/roc_auc_curve.png)

---

## 🔭 Future Work

- Expand model to multi-day survival prediction  
- Add time-series vitals data if available  
- Compare performance with deep learning models  
- Build dashboard using Streamlit for hospital integration  

---

## 📬 Contact

**Nguyen Gia Khiem**  
3rd-year student – Electronic Physics Technology and Informatics  
📍 Ho Chi Minh City, Vietnam  
🔗 GitHub: [github.com/Boong27](https://github.com/Boong27)  
✉️ Giakhiem@gmail.com

---

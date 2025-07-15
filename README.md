# 🚨 Fraudulent Claim Detection – Machine Learning Project

## 📌 Objective
The goal of this project is to detect fraudulent insurance claims using machine learning. By leveraging customer profiles, claim attributes, and incident details, we aim to build models that can flag potential fraud early in the claim approval process.

---

## 📁 Repository Contents

> All files are packaged inside the ZIP archive:  
> **`Fraudulent_Claim_Detection_Umair_Birajdar.zip`**

| File | Description |
|------|-------------|
| `Fraudulent_Claim_Detection_Starter.ipynb` | Main Jupyter notebook containing data cleaning, EDA, feature engineering, model building, and evaluation. |
| `Fraudulent_Claim_Detection_Starter.pdf` | Well-formatted PDF report generated from the notebook. |
| `Fraudulent_Claim_Detection_Presentation.pptx` | Summary PowerPoint presentation highlighting business problem, approach, key findings, and recommendations. |

---

## 🧠 Project Workflow

1. **Data Preparation**
   - Read and explored dataset of 1000 rows and 40 columns
   - Checked for missing/null values and cleaned data accordingly

2. **EDA (Exploratory Data Analysis)**
   - Performed univariate and bivariate analysis
   - Visualized class imbalance and feature-target relationships

3. **Feature Engineering**
   - Created ratio features and time-based features
   - Handled high-cardinality categorical variables
   - Applied dummy encoding and scaling

4. **Modeling**
   - **Logistic Regression** with RFECV for feature selection, VIF, and p-values
   - **Random Forest** with feature importance and hyperparameter tuning

5. **Model Evaluation**
   - Compared models using accuracy, precision, recall, and F1-score
   - Identified optimal cutoff using sensitivity-specificity trade-off

---

## 📊 Results Summary

| Metric       | Logistic Regression | Random Forest |
|--------------|---------------------|----------------|
| Accuracy     | 89.18%              | 80.33%         |
| Precision    | 87.61%              | 64.71%         |
| Recall       | 91.27%              | 44.59%         |

✅ **Logistic Regression** performed better and was selected for deployment.

---

## 💡 Business Implications

- Early detection of fraud can save millions in payouts
- Models provide real-time risk scoring for incoming claims
- Enhances operational efficiency and customer trust

---

## 🎯 Recommendations

- Adopt Logistic Regression model for deployment
- Integrate model into claim management systems
- Improve data quality by reducing missing entries
- Periodically retrain the model with new data

---

## 👤 Author

**Umair Birajdar**  
Executive Diploma in Data Science & AI – IIITB & upGrad  
Aug 2025

---

## 📄 License

This project is for academic and educational use only.

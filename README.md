---

# 🎯 Terrorism Risk Level Prediction (Basic ML Project)

This project builds a **Random Forest Classifier** to predict the **Risk Level** (No Risk, Low, Medium, High) of terrorism incidents based on features extracted from real-world data.

---

## 📑 Project Overview

- **Objective**: Predict the severity ("Risk Level") of terrorism incidents using Machine Learning.
- **Model Used**: Random Forest Classifier
- **Target Classes**:
  - No Risk (0 casualties)
  - Low Risk (1–5 casualties)
  - Medium Risk (6–20 casualties)
  - High Risk (>20 casualties)

---

## 🛠️ Workflow Completed
1. **Data Loading**: Read dataset from CSV.
2. **Feature Engineering**:
   - Extracted `Year` and `Month` from `Date`.
   - Created a new `Risk Level` feature based on `Casualties`.
3. **Data Preprocessing**:
   - Encoded categorical variables using Label Encoding.
4. **Model Building**:
   - Trained a **Random Forest Classifier**.
5. **Model Evaluation**:
   - Measured performance using **Accuracy**, **Classification Report**, and **Confusion Matrix**.

---

## 🧪 Libraries Used
- Python 3.x
- pandas
- scikit-learn

---



---

## 📌 Notes
- Categorical columns like `State`, `City`, `Attack Type`, etc., were label-encoded.
- Target column (`Risk Level`) was also encoded for classification.
- Random Forest was chosen because of its robustness and ability to handle mixed-type data.

---

## 📚 Future Enhancements (Optional)
- Hyperparameter tuning of Random Forest.
- Trying other ML models (XGBoost, Decision Trees, etc.).
- Build a simple **Streamlit app** to interact with the model.

---

# 🛡️ License
This project is for educational purposes.

---



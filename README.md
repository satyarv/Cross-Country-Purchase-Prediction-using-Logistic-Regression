# Cross-Country-Purchase-Prediction-using-Logistic-Regression
A logistic regression model was built using a Japanese customer dataset to predict purchase behavior based on features like age, income, gender, and car age. The trained model was then applied to an Indian dataset to identify potential customers likely to make a purchase, enabling cross-market behavior prediction

# 🚗 Capstone Project: Market Entry Analysis for ABG Motors in India

This project uses machine learning to analyze the **Indian automotive market** and predict customer purchase behavior, based on patterns learned from **Japanese customer data**. It was developed as a capstone project for the B.Tech final year.

---

## 🎯 Objective

To help **ABG Motors** evaluate market potential in India by building a machine learning model trained on Japanese consumer data and applying it to Indian customer profiles to predict vehicle purchase decisions.

---

## 📁 Datasets

- **Japanese Dataset**:  
  - Features: `CURR_AGE`, `ANN_INCOME`, `GENDER`, `AGE_CAR`, `PURCHASE`  
  - Used for training

- **Indian Dataset**:  
  - Features: `CURR_AGE`, `ANN_INCOME`, `GENDER`, `AGE_CAR`  
  - Target: Predict `PURCHASE` using model trained on Japanese data

---

## 🧰 Tools & Libraries

- Python (Google Colab)
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🛠️ ML Pipeline

1. Data Cleaning & Preprocessing  
   - Encoding categorical variables  
   - Feature scaling using StandardScaler  
2. Model Training  
   - Trained **Logistic Regression** on Japanese dataset  
3. Prediction  
   - Applied the trained model to Indian dataset  
4. Evaluation  
   - Predicted purchase intent:  
     - `PURCHASE = 1` → 23,031 customers  
     - `PURCHASE = 0` → 16,969 customers  

---

## 🤖 Model Used

- **Logistic Regression**

---

## 📈 Results

- Successfully predicted purchase behavior on Indian dataset using Japanese-trained model
- Provided strategic insights for market entry decisions

---

## 📌 Challenges Faced

- Aligning feature distributions between countries
- Generalizing a model across different customer demographics

---

## 🚀 Future Work

- Use more advanced models like XGBoost or Random Forest
- Analyze cultural and economic differences in depth
- Build a dashboard or interface for business stakeholders

---

## 👤 Author

- Satya Ganesh  
- B.Tech CSE, ICFAI Tech, 2026  
- Tools: Python, Google Colab  
- Area: Machine Learning, Market Analytics

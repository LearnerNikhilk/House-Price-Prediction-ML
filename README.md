# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview
This project predicts residential house prices using Machine Learning regression models. It analyzes features like area, number of rooms, and location to estimate property prices.

---

## 📊 Dataset
- Source: Kaggle Housing Dataset  
- Records: 1460 rows  
- Features: 80 variables (numerical + categorical)

---

## 🧹 Data Preprocessing
- Handled missing values
- Removed outliers
- Feature encoding (categorical → numerical)
- Feature scaling

---

## 📈 Exploratory Data Analysis (EDA)
- Correlation heatmap
- Distribution plots
- Feature importance analysis

---

## 🤖 Models Used
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

---

## 📏 Model Evaluation

| Model               | R² Score |
|--------------------|----------|
| Linear Regression  | 0.78     |
| Decision Tree      | 0.85     |
| Random Forest      | 0.91     |

✅ Random Forest performed best.

---

## 🔍 Sample Prediction
Input:
- Area: 2000 sqft  
- Bedrooms: 3  
- Location: Urban  

Output:
- Predicted Price: ₹75 Lakhs (approx)

---

## 🚀 Deployment
🔗 Live Demo: [Add your deployed link here]

(Deployed using Lovable.dev / Streamlit)

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## ▶️ How to Run
```bash
git clone https://github.com/your-username/House-Price-Prediction-ML
cd House-Price-Prediction-ML
pip install -r requirements.txt
python app.py

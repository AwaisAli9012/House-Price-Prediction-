# 🏠 Housing Price Prediction

This project builds and evaluates two regression models — **Linear Regression** and **Gradient Boosting Regressor** — to predict housing prices based on features like area, bedrooms, location, and furnishing status.

---

## 📌 Dataset

The dataset (`Housing.csv`) includes features such as:
- `area`, `bedrooms`, `bathrooms`, `stories`, `parking`
- Binary columns like `mainroad`, `guestroom`, `basement`, etc.
- Categorical column: `furnishingstatus`
- Target column: `price`

---

## ⚙️ Steps Performed

1. **Data Preprocessing**
   - Binary encoding for yes/no columns
   - One-hot encoding for `furnishingstatus`
   - Feature scaling using `StandardScaler()`

2. **Train-Test Split**
   - 80% training, 20% testing

3. **Model Training**
   - Linear Regression
   - Gradient Boosting Regressor (100 estimators)

4. **Evaluation Metrics**
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)
   - R² Score

5. **Visualization**
   - Actual vs. Predicted prices for both models using scatter plots

---

## 📈 Results (Sample Output)

- Visual comparison between actual and predicted prices
- Evaluation metrics printed in the terminal

---

## 🧪 Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

## 🚀 How to Run

1. Clone the repo and place `Housing.csv` in the same directory.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

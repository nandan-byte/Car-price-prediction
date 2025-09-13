# 🚗 Car Price Prediction  

This project predicts the **price of used cars** based on their features such as brand, year, kilometers driven, and fuel type.  
The dataset was taken from **Quikr Car Listings**, cleaned, and modeled using **Linear Regression** with preprocessing handled through a **Pipeline**.  

---

## 📌 Features of the Project
- Data Cleaning & Preprocessing  
  - Removed missing/invalid values (e.g., “Ask For Price”)  
  - Converted `year`, `kms_driven`, and `Price` to numeric values  
  - Simplified car names for consistency  
- Exploratory Data Analysis (EDA) with **Seaborn** & **Matplotlib**  
- Model Building using **Linear Regression**  
- Used **Pipeline + OneHotEncoder** to handle categorical variables  
- Model Evaluation with **R² Score**  
- Saved trained model with **Pickle** for deployment  

---

## 🛠️ Tech Stack
- **Python 3**  
- **Pandas**, **NumPy** → Data manipulation  
- **Matplotlib**, **Seaborn** → Data visualization  
- **Scikit-Learn** → Machine Learning (Linear Regression, OneHotEncoding, Pipeline)  
- **Pickle** → Model serialization  

---

## 📊 Results

Best achieved R² score ≈ 0.89 after multiple train-test splits.

Model predicts realistic prices for unseen cars.

---

## 🔮 Future Improvements

Try advanced models like Random Forest or XGBoost

Add more features (e.g., transmission type, owner history)

Deploy as a Flask / FastAPI web app

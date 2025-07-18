# 🏡 Housing Price Prediction Model

This project is a **Housing Price Prediction System** using a machine learning regression model. It takes house-related features and predicts the price of a house using a trained ML model saved as `housing_model.joblib`.

---

##  Model Performance

- **Training R² Score**: `0.6529` (~65.29%)
- **Testing R² Score**: `0.6859` (~68.59%)

This shows a moderate fit — the model can explain about 68% of the variance in unseen data.

---

##  Dataset

> The dataset includes features such as:
- Number of rooms
- Area (in square feet)
- Number of bathrooms
- Age of the house
- Location (optional, if encoded)

---

##  Tech Stack

- **Python 3.8+**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Joblib** (to save the model)

---

## Model Info

- **Model Used**: Linear Regression 
- **Serialization**: `joblib`
- **File**: `housing_model.joblib`




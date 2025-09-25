# House Price Prediction with Multi-Layer Perceptron (MLP)

This project uses **neural networks (MLPRegressor)** to predict house prices based on key features such as bedrooms, bathrooms, and living area size.  
It was developed as part of my **Data Mining** course to practice regression modeling and performance evaluation.

---

## 📚 Overview
- Imported and cleaned the **kc_house_data.csv** dataset
- Selected relevant features: `bedrooms`, `bathrooms`, `sqft_living15`, `sqft_lot15`, `price`
- Filled missing values with column means
- Split data into **70/30 train/test sets**
- Trained three different **MLPRegressor** models with varying hidden layer sizes
- Evaluated models with **Mean Squared Error (MSE)**
- Visualized training vs. testing error curves to determine best network configuration

---

## 🛠️ Technologies Used
- **Python 3.x**
- **Google Colab**
- **Libraries:** `scikit-learn`, `numpy`, `pandas`, `matplotlib`

---

## ▶️ Run the Notebook
Open the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/benkosiek/b074840a8af0667dc27fda36dbbefae9/lab9_exercise.ipynb)



## 📝 Key Insights
- Increasing the number of neurons generally reduced training error
- Identified an optimal range for hidden layer size that balanced training and test performance (avoiding overfitting)
- Demonstrated the importance of preprocessing and proper train/test split for regression tasks

---

## 📂 Files in This Repository
- `house_price_prediction_mlp.ipynb` – Main notebook with code, results, and visualizations

---

## 🚀 Future Work
- Add hyperparameter tuning (learning rate, regularization) using GridSearchCV
- Compare MLP performance with Linear Regression, Decision Tree Regressors, or Random Forests
- Incorporate additional features to improve accuracy

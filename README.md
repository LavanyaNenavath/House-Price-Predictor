# 🏠 House Price Prediction using USA Housing Dataset

# 📌 Project Overview

Predicting house prices accurately is an important challenge in the real estate market.  
This project uses **Machine Learning techniques** to estimate house prices based on several factors such as income, population, and number of rooms.

The model is trained using the **USA Housing Dataset** and applies **Linear Regression** to predict house prices.

---

# 🎯 Objective

The main objective of this project is to:

- Predict house prices based on housing features.
- Understand which factors influence house prices the most.
- Evaluate model performance using regression evaluation metrics.

This is a **Regression Problem** where the target variable is the **House Price**.

---

# 📂 Dataset Information

**Dataset Name:** `USA_Housing.csv`  
**Source:** Kaggle  

### Dataset Features

| Feature | Description |
|------|------|
| Avg. Area Income | Average income of people living in the area |
| Avg. Area House Age | Average age of houses in the area |
| Avg. Area Number of Rooms | Average number of rooms per house |
| Avg. Area Number of Bedrooms | Average number of bedrooms |
| Area Population | Total population in the area |
| Address | Address of the house (removed during modeling) |
| Price | Target variable (house price) |

Dataset contains **~5000 records and 7 features**.

---

# ⚙️ Project Workflow

## 1️⃣ Data Preprocessing

- Loaded dataset using **Pandas**
- Removed **Address column** (non-numeric)
- Checked for missing values
- Split dataset into:
  - **80% Training Data**
  - **20% Testing Data**

---

## 2️⃣ Exploratory Data Analysis (EDA)

EDA was performed using **Matplotlib and Seaborn**.

The following visualizations were created:

- Histogram of house prices
- Correlation heatmap
- Scatter plot (Price vs Income)
- Scatter plot (Price vs Rooms)

### Key Insights

- **Average Area Income** strongly affects house price
- **Number of Rooms** also shows strong correlation with price
- Higher income areas tend to have higher house prices

---

# 🤖 Machine Learning Model

### Model Used
**Linear Regression**

Linear Regression is used to model the relationship between housing features and house price.

---

# 📈 Model Evaluation

The model performance was evaluated using the following metrics:

| Metric | Value |
|------|------|
| MAE (Mean Absolute Error) | ~81,000 |
| RMSE (Root Mean Squared Error) | ~102,000 |
| R² Score | ~0.91 |

### Interpretation

- The model explains **~91% of the variance in house prices**
- Predicted values are close to actual prices
- Linear Regression performs well for this dataset

---

# 📊 Visualizations

### Distribution of House Prices
Shows most houses fall in the **mid-price range with some high-value outliers**.

### Correlation Heatmap
Shows strong positive correlation between:

- **Average Area Income**
- **Average Area Number of Rooms**
- **House Price**

### Scatter Plot (Price vs Income)
Higher income areas generally have **higher house prices**.

### Scatter Plot (Price vs Rooms)
Houses with **more rooms tend to be more expensive**.

### Actual vs Predicted Plot
Predicted prices closely match actual prices, indicating **good model accuracy**.

---

# 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 🚀 How to Run the Project

1. Clone the repository

```
git clone https://github.com/your-username/house-price-prediction.git
```

2. Install required libraries

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the Python script or Jupyter Notebook.

---

# 📌 Future Improvements

The model can be improved by using advanced machine learning algorithms such as:

- Random Forest Regressor
- Gradient Boosting
- XGBoost

These models may provide **higher prediction accuracy**.

---

# 📜 Conclusion

This project successfully built a **Linear Regression model** to predict house prices using the **USA Housing dataset**.

The analysis revealed that:

- **Average Area Income**
- **Average Area Number of Rooms**

are the most influential factors affecting house prices.

The model achieved **high prediction accuracy**, demonstrating that regression techniques can effectively estimate real estate prices.

---

⭐ If you like this project, consider giving the repository a **star**!

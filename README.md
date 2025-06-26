🏠 Task 3: Linear Regression - House Price Prediction

This project is part of an internship task to implement and understand **simple and multiple linear regression** using a real-world dataset.

📂 Dataset

The dataset used is [`Housing.csv`] which contains house features such as area, bedrooms, bathrooms, furnishing status, etc., and their corresponding prices.

🎯 Objective

- Predict house prices based on given features using Linear Regression.
- Learn how to evaluate regression models using standard metrics.


 🛠 Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn


 ✅ Steps Performed

1. Loaded the dataset using pandas.
2. Explored the data using ".info()" and ".describe()".
3. Handled missing values and categorical variables using "dropna()" and "pd.get_dummies()".
4. Split data into training and testing sets using "train_test_split()".
5. Trained a Linear Regression model  using "LinearRegression()" from scikit-learn.
6. Evaluated the model using:
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - R² Score
7. Interpreted coefficients to understand feature impact.
8. Visualized results with a regression line (for simple regression).

---

 📈 Evaluation Metrics

- MAE :  970043.4039201637
- MSE  : 1754318687330.6646
- R² Score : 0.6529242642153182

🔍 Observations

- Linear regression showed a decent fit based on R² score.
- Features like area and furnishing status had stronger influence on price.
- Categorical data was handled using one-hot encoding.
- Model performance depends on input feature quality and quantity.


 📁 Files in This Repo

- 'Housing.csv' – Original dataset
- 'Housing_cleaned.csv' – Cleaned/preprocessed version
- 'linear_regression.ipynb' – Jupyter notebook with code
- 'README.md' – This file



 🙋‍♀️ Author

This project was completed as part of my internship tasks.


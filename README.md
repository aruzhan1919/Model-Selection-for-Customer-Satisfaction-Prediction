**Customer Satisfaction Prediction**

This project explores probabilistic modeling of customer satisfaction using machine learning. The goal is to predict satisfaction scores based on customer features such as income, product quality, service quality, age, and purchase frequency.

**Project Overview**

The notebook includes:

Exploratory Data Analysis (EDA): To understand data distributions and detect patterns.

Correlation Analysis: To assess which features most influence satisfaction.

Feature Selection: Based on correlation and feature importance.

Modeling: Four regression models are evaluated:

K-Nearest Neighbors Regressor

Random Forest Regressor

Lasso Regression

Neural Network (MLP)

Each model is optimized using GridSearchCV and evaluated using Mean Squared Error (MSE) and R² score.

**Results**

Random Forest Regressor yielded the best performance with an R² score of approximately 0.76.

The most impactful features were ServiceQuality, ProductQuality, and Income.

**Technologies Used**

Python, NumPy, Pandas, Matplotlib, Seaborn

Scikit-learn (for classical ML)

TensorFlow/Keras (for neural network)

Jupyter Notebook

**File Structure**

ML_Project.ipynb – Main notebook containing code and results

real_estate_data.csv – Sample dataset (if applicable)

README.md – Project overview and setup instructions

How to Run
Clone this repository

Install dependencies listed in the notebook

Run ML_Project.ipynb in Jupyter or Google Colab

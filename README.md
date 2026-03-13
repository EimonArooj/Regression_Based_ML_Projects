# Regression-Based Machine Learning Projects

This repository contains multiple machine learning projects focused on **predicting continuous numerical values using regression models**.
Each project follows a complete **data science workflow**, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction.

These projects were developed as practical implementations while learning machine learning and data science concepts.

# Projects Included

## 1. Car Price Prediction

This project predicts the **selling price of used cars** based on several features such as fuel type, transmission, kilometers driven, and ownership history.

### Key Steps

* Data preprocessing and cleaning
* Exploratory Data Analysis using histograms, scatter plots, and box plots
* Encoding categorical variables
* Feature scaling
* Model training using Random Forest

### Algorithm Used

* Random Forest Regressor

### Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

---

## 2. Flight Fare Prediction

This project predicts **airline ticket prices** based on factors like airline, travel class, route, duration, and number of stops.

### Key Steps

* Data cleaning and handling missing values
* Feature engineering (duration conversion, route creation)
* One-hot encoding of categorical variables
* Visualization of airline price trends and route patterns
* Model training and hyperparameter tuning

### Algorithms Used

* Random Forest Regressor
* GridSearchCV for hyperparameter optimization

### Additional Feature

* Interactive **user input prediction system**
* Trained model saved using `joblib`

---

## 3. House Price Prediction

This project predicts **house prices** using features such as location, area, number of rooms, nearby schools, house condition, and year built.

### Key Steps

* Mutual Information analysis for feature importance
* Data visualization using Matplotlib, Seaborn, and Plotly
* Feature engineering and categorical encoding
* Model training using Linear Regression
* User input-based house price prediction

### Algorithm Used

* Linear Regression

---

## 4. Salary Prediction

This project estimates **employee salaries** based on factors such as age, experience, education level, and gender.

### Key Steps

* Data cleaning and missing value handling
* Outlier detection using boxplots and IQR
* Exploratory Data Analysis (EDA)
* Feature engineering (experience level, age groups)
* Encoding categorical variables
* Feature scaling

### Algorithm Used

* Linear Regression

### Additional Features

* Model saving using `joblib`
* User input salary prediction system

---

## 5. Sales Prediction

This project predicts **product sales** based on advertising expenditures across different marketing channels.

### Key Steps

* Feature selection
* Train-test split
* Model training using Linear Regression
* Model evaluation using regression metrics

### Algorithm Used

* Linear Regression

---

## 6. Stock Trend Prediction

This project predicts **future stock closing prices** using historical stock data and engineered financial indicators.

### Key Steps

* Time series preprocessing
* Feature engineering using financial indicators:

  * Moving averages
  * Daily returns
  * Momentum
  * Volatility
* Time-based train-test split
* Model evaluation and visualization of predicted vs actual prices

### Algorithm Used

* Linear Regression

---

# Technologies and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn
* Joblib

---

# Machine Learning Concepts Applied

The projects implement several machine learning techniques including:

* Linear Regression
* Random Forest
* Feature Engineering
* Data Preprocessing
* Hyperparameter Tuning
* Model Evaluation

---

# Workflow Followed in Projects

Most projects follow the standard machine learning pipeline:

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Prediction System / Model Deployment

---

# Evaluation Metrics Used

The following regression metrics were used to evaluate model performance:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

# Overall Conclusion

These projects demonstrate practical experience in building **end-to-end regression-based machine learning systems** using real-world datasets. Through these implementations, important concepts such as data preprocessing, feature engineering, model selection, and evaluation were explored.

Working on multiple prediction problems—such as car prices, flight fares, salaries, house prices, sales forecasting, and stock trends—helped develop a deeper understanding of how regression algorithms can model relationships between variables and generate meaningful predictions.

Overall, this repository showcases hands-on experience in building machine learning pipelines and applying regression techniques to solve diverse real-world prediction problems.

---

# Future Improvements

Possible improvements for these projects include:

* Adding deep learning models
* Deploying models using web frameworks
* Building interactive dashboards
* Integrating real-time data sources
* Creating web-based prediction systems

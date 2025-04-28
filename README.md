# TASK-3-Data-Modelling
# Housing Price Prediction
This project predicts housing prices using various regression models based on features such as the number of bedrooms, bathrooms, location attributes, and more. The dataset comes from Kaggle and includes housing data with both numerical and categorical features.

# Dataset
Source: harishkumardatalab/housing-price-prediction

The dataset includes features such as:

bedrooms, bathrooms, stories

mainroad, guestroom, basement, hotwaterheating, airconditioning

furnishingstatus, prefarea

parking, area, and price (target)

# Libraries Used
numpy, pandas — for data manipulation

matplotlib, seaborn — for data visualization

scikit-learn — for preprocessing, modeling, and evaluation

# Models Used
The following regression models were trained and evaluated using the R² score:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Support Vector Regressor (SVR)

Gradient Boosting Regressor

AdaBoost Regressor

# Evaluation Metric
R² Score (Coefficient of Determination): Used to evaluate how well the models predict house prices.

Data was scaled using MinMaxScaler to normalize features.

Label encoding was applied to convert categorical variables.

# How to Run
Download the dataset from Kaggle.

Ensure all required libraries are installed (pandas, sklearn, etc.).

Run the Python notebook or script:

bash
Copy
Edit
python housing_price_prediction.py
The script includes:

Data loading and cleaning

Exploratory Data Analysis (EDA)

Feature encoding and scaling

Model training and evaluation

Visualization of model performance

# Sample Output
At the end, the R² scores for each model are printed to compare their performance:

text
Copy
Edit
Model Performance (R² Score):
Linear Regression:       0.6523
Decision Tree:           0.7812
Random Forest:           0.8720
Support Vector Regressor:0.6415
Gradient Boosting:       0.8748
AdaBoost:                0.7934

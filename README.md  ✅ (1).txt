PROJECT: California Housing Price Prediction using Linear Regression

OBJECTIVE:
The objective of this project is to understand the complete Machine Learning workflow including data loading, preprocessing, training, evaluation, and visualization. A Linear Regression model is used to predict housing prices.

TOOLS AND TECHNOLOGIES USED:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

DATASET:
- California Housing Dataset
- Loaded from a CSV file (housing.csv)

STEPS PERFORMED:

1. IMPORT LIBRARIES
Imported all required libraries for data handling, visualization, and machine learning.

2. LOAD DATASET
Loaded the dataset using pandas:
df = pd.read_csv("housing.csv")

3. DATA CLEANING
- Checked dataset structure using df.info()
- Viewed statistical summary using df.describe()
- Handled missing values using:
  df.fillna(df.mean(), inplace=True)

4. EXPLORATORY DATA ANALYSIS (EDA)
- Generated correlation heatmap using seaborn
- Observed relationships between different features

5. FEATURE SELECTION
- Selected independent variables (X)
- Selected target variable (y = median_house_value)

6. TRAIN-TEST SPLIT
- Split data into training (80%) and testing (20%) sets

7. MODEL TRAINING
- Used Linear Regression model
- Trained the model using training data

8. PREDICTION
- Predicted housing prices using test data

9. MODEL EVALUATION
- Evaluated model using:
  • Mean Absolute Error (MAE)
  • Root Mean Squared Error (RMSE)
  • R² Score

10. VISUALIZATION
- Plotted Actual vs Predicted values
- Created residual plot to analyze errors

RESULT:
The Linear Regression model was successfully trained and evaluated. The model shows reasonable performance in predicting housing prices.

FILES INCLUDED:
- task1_ml_linear_regression.ipynb (Jupyter Notebook)
- housing.csv (Dataset)
- README.txt (Project Description)

CONCLUSION:
This project successfully demonstrates the implementation of a complete machine learning pipeline using Linear Regression on a real-world dataset.

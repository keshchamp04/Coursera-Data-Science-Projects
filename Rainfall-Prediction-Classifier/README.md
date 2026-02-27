# Rainfall Prediction Classifier (Australia Weather Dataset)

## Objective
To build a machine learning classification model that predicts whether it will rain the next day based on historical weather data.

The goal is to analyze meteorological features and develop a predictive model that can classify rainfall occurrence accurately.

## Dataset
The dataset contains historical daily weather observations from multiple locations in Australia, including:

- Temperature (MinTemp, MaxTemp)
- Humidity (Morning & Afternoon)
- Wind Speed & Direction
- Atmospheric Pressure
- Cloud Cover
- Rainfall (mm)
- Target Variable: RainTomorrow (Yes/No)

The dataset includes both numerical and categorical features, requiring preprocessing before model training.

## Techniques Used
- Data cleaning and handling missing values
- Encoding categorical variables
- Feature selection and preprocessing
- Train-test split
- Classification modeling (e.g., Logistic Regression / KNN / Decision Tree)
- Model evaluation using accuracy and confusion matrix

## Model Evaluation
- Accuracy score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

## Key Insights
- Humidity and pressure are strong indicators of next-day rainfall.
- Proper handling of missing values significantly improves model performance.
- Feature scaling improves performance for distance-based models like KNN.
- Class imbalance affects prediction accuracy and must be considered.

## Tools
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

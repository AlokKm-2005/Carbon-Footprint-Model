How to Run the Model
The core of the project is a Python script that handles data preprocessing, model training, and prediction. The following steps show the complete process.

1. Data Preprocessing and Cleaning
This step prepares the raw data by handling missing values and dropping irrelevant columns. It ensures the data is in a clean format suitable for model training.

2. Feature Engineering and Selection
We define the Total emissions as the target variable (y) and use columns like Year, Coal, Oil, Gas, Cement, and Flaring as the input features (X).

3. Data Splitting
The dataset is divided into a training set and a testing set (80/20 split) to allow for unbiased model evaluation.

4. Model Training and Saving
A LinearRegression model is trained on the training data and then saved to a file named carbon_footprint_model.pkl using joblib.

5. Making Predictions
The saved model is loaded and used to make predictions on a new, unseen data point.

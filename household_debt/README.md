
# Household Debt-to-Income Ratios: 1999-Q1 2023

## 1. **Inspecting the Dataset**:

### a. Initial Glance:
- Started my initial EDA using a ProfileReport from ydata (10/25/23)
 
### b. Summary Statistics:
- For numerical data: mean, median, min, max, standard deviation.
- For categorical data: unique values, count of each value.

### c. Missing Values:
- Largest missing values in "high" column
- Going to impute these missing cells with the mean of the previous three years and the next found value for that given county. (11/15/23)
- That got us down to appx 4% missing values in the high column. I decided to drop those rows because not having them does not hurt the project but attempting to impute them would prove difficult.

### d. Visualization:
- YData ProfileReport does this automatically

## 2. **Identify Potential Problems or Questions**:

### a. Classification:
- Is there a categorical column that can be predicted based on other features?
- Example: Predicting if a person will default on a loan.

### b. Regression:
- Is there a numerical column that can be predicted?
- Example: Predicting house prices based on features.

### c. Clustering:
- Are there any interesting patterns or groups in the data?
- Example: Customer segmentation.

### d. Anomaly Detection:
- Are there any outliers or anomalies in the data?
- Example: Detecting fraudulent transactions.

## 3. **Data Preprocessing**:

### a. Handle Missing Data:
- Impute or drop based on the nature of the dataset.

### b. Feature Engineering:
- Create new features that might be helpful.
- Example: Extracting day, month, year from a date column.

### c. Categorical Data:
- Convert categorical data into numerical format using encoding techniques like One-Hot Encoding or Label Encoding.

### d. Scaling:
- Standardize or normalize data if necessary.

## 4. **Modeling**:

### a. Choose a Relevant Algorithm:
- Based on the problem (classification, regression, clustering).

### b. Train/Test Split:
- Split the data into training and testing sets.

### c. Model Training:
- Train the model on the training data.

### d. Model Evaluation:
- Evaluate the model using appropriate metrics.
- For classification: accuracy, precision, recall, F1 score, ROC curve.
- For regression: MSE, RMSE, MAE, R^2.

### e. Hyperparameter Tuning (Optional):
- Use techniques like Grid Search or Random Search to find the best parameters.

## 5. **Documenting Your Findings**:

### a. Introduction:
- Briefly describe the dataset and the problem.

### b. Data Exploration:
- Include visualizations and summary statistics.

### c. Data Preprocessing:
- Describe steps taken and why.

### d. Modeling:
- Describe the algorithm, hyperparameters, and evaluation metrics.

### e. Conclusion:
- Summarize the results and any potential improvements.

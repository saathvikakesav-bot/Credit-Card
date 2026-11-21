Credit Card Default Prediction
Project Overview
This project analyses credit-card customer data and uses machine-learning models to predict whether a customer may default on their payment next month.
Objective
To predict whether a customer will default on their next month's payment.
- 0 – No default
- 1 – Default
Dataset
The project uses creditcard.csv, which contains customer details, credit limits, repayment status, bill amounts, and previous payment amounts.
Tools and Libraries
- Python
- Jupyter Notebook
- NumPy and Pandas
- Matplotlib and Seaborn
- Scikit-learn
Project Workflow
1. Import the required libraries and load the dataset.
2. Explore the data using summary statistics and dataset information.
3. Check for missing values, duplicates, and outliers.
4. Visualise the target distribution and important features.
5. Separate the input features (X) and target (y).
6. Apply feature selection using SelectKBest.
7. Split the data into training and testing sets.
8. Train and compare Logistic Regression, Decision Tree, and Random Forest models.
9. Evaluate the models using accuracy, precision, recall, and F1-score.
Conclusion
This project uses data analysis and classification models to predict credit-card payment defaults. The model results help compare how effectively each algorithm identifies potential defaults.

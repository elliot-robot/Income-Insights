# Income Insights
 Predictive Modeling for Salary Classification


This project focuses on predicting individual income levels (greater than 50K or not) using machine learning techniques. The dataset, stored in income.csv, was preprocessed to handle missing values, duplicates, and categorical variables. Key steps included renaming columns, encoding categorical data, and normalizing features. The dataset was split into training (90%) and testing (10%) sets. Three models were evaluated: Logistic Regression (81% accuracy), Support Vector Machine (79.5% accuracy), and K-Means clustering (72% accuracy). Parameter tuning and 10-fold cross-validation were applied to optimize performance, with Logistic Regression achieving the highest accuracy.

Technical Details:
The project employed scikit-learn for model implementation. Logistic Regression and SVM were fine-tuned using GridSearchCV, while K-Means clustered data into two groups based on income. The heuristic function in A* search guided the solution for the "Farmer, Wolf, Goat, and Cabbage" problem, ensuring safe state transitions. The report highlights the importance of normalization, cross-validation, and hyperparameter tuning in improving model accuracy. The code and detailed analysis are documented in Jupyter notebooks, with results summarized in tables for clarity.

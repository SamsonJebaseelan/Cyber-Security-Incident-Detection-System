Project Title
-------------
Microsoft -Classifying Cybersecurity Incidents

Project Overview
----------------
This project aims to build and evaluate machine learning models to identify fraudulent transactions in financial data. The objective is to detect fraud effectively using various classification algorithms and compare their performance to select the best model for deployment.

Objectives
-----------
- Data Exploration: Analyze and preprocess the dataset to prepare it for model training.
- Model Training: Implement and train multiple machine learning models to detect fraud.
- Model Evaluation: Compare model performance using various metrics to identify the best-performing model.

Dataset
--------
- train.csv: Contains historical transaction data with labels indicating whether a transaction is fraudulent or not.
- test.csv: Contains data used for evaluating the final model.

Jupyter Notebook
----------------
1. Open the Jupyter Notebook:
   - Navigate to the project directory where your Jupyter Notebook file is located.
   - Launch Jupyter Notebook by running the following command in your terminal:
     jupyter notebook
   - Open the notebook file (e.g., `microsoft_model.ipynb`).

2. Execute the Cells:
   - Run each cell sequentially by selecting the cell and pressing `Shift + Enter`.
   - The notebook includes sections for data exploration, preprocessing, model training, and evaluation.

3. View Results:
   - The notebook will display outputs and performance metrics for each model, including accuracy, precision, recall, and f1-score.

Models Implemented
------------------
1. Logistic Regression
2. Random Forest
3. Decision Tree
4. XGBoost
5. LightGBM

Results
--------
- Logistic Regression: Accuracy: 52.56%
- Random Forest: Accuracy: 77.59%
- Decision Tree: Accuracy: 77.40%
- XGBoost: Accuracy: 91.73%
- LightGBM: Accuracy: 89.52%

Problems Faced
---------------
- Data Quality Issues: Missing values and class imbalance required additional preprocessing steps.
- Model Performance Challenges: Some models exhibited overfitting and required hyperparameter tuning.
- Computational Resources: Training complex models was resource-intensive.
- Evaluation Metrics: Interpreting results from advanced models was challenging.
- Deployment Considerations: Ensuring scalability and integration into production systems.

Lessons Learned
----------------
- Data Preparation: Essential for reliable model performance.
- Model Selection: Requires careful consideration and tuning.
- Resource Management: Crucial for handling large-scale tasks.






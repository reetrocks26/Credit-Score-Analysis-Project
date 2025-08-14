# Credit Score Analysis Project

## Objective
The goal of this project is to explore and understand how credit score algorithms work. We develop models from scratch to predict creditworthiness using the German Credit Dataset. This project demonstrates the full workflow, from data exploration to model evaluation and feature analysis.

## Dataset
- **File:** `german_credit.csv`
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))
- The dataset contains information about 1000 individuals with 20 attributes each, including financial, personal, and credit-related details.
- The target variable indicates whether a person is a good or bad credit risk.

## Methodology
1. **Data Exploration**: Understanding the structure, checking missing values, and visualizing distributions.
2. **Preprocessing**: Encoding categorical variables, splitting features and target, and scaling numeric columns.
3. **Model Building**: Implementing multiple models like Logistic Regression, Decision Tree, and Random Forest.
4. **Evaluation**: Measuring performance using accuracy, classification report, and confusion matrices.
5. **Feature Analysis**: Identifying which features most influence creditworthiness using feature importance from Random Forest.

## How to Run
1. Open the notebook: `notebooks/credit_score_analysis.ipynb` in Jupyter Notebook.
2. Make sure required Python libraries (`pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`) are installed.
3. Run the notebook cells step by step to reproduce the analysis and results.

## Project Outcome
By the end of this project, we have a working credit scoring model and insights into which factors affect creditworthiness the most. This can help in understanding the decision-making process behind credit approvals.

## GitHub Repository
All project files including the notebook and dataset are available here:  
[Credit Score Analysis Repository](https://github.com/reetrocks26/Credit-Score-Analysis-Project)

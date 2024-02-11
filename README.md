# Loan Approval Project
Overview
This project focuses on predicting loan approval using machine learning techniques. It includes data preprocessing, exploratory data analysis, model training, and evaluation.

# Table of Contents
Data
Data Preparation
Data Exploration
Data Preprocessing
Model Training
Model Evaluation
Next Steps
Dependencies
How to Use
Contributing
License
Data
The dataset (loan.csv) consists of information related to loan applicants, including features such as gender, marital status, income, loan amount, and approval status.

# Data Preparation
The data was cleaned by handling missing values and creating new features such as 'loanAmount_log' and 'TotalIncome'. The dataset was split into training and testing sets.

# Data Exploration
Exploratory data analysis was performed to understand the distribution of loan amounts and the count of people taking loans based on gender.

# Data Preprocessing
Categorical variables were encoded using Label Encoding, and missing values were imputed. The dataset is now ready for machine learning.

# Model Training
A Gaussian Naive Bayes classifier was chosen for its simplicity and efficiency. The model was trained on the prepared data.

# Model Evaluation
The model achieved an accuracy of approximately 82.93% on the test set. Further evaluation metrics can be explored, and the model's performance can be analyzed in more detail.

# Next Steps
Future steps may include exploring other classification algorithms, fine-tuning hyperparameters, and analyzing misclassifications for model improvement.

# Dependencies
Python 3.x
scikit-learn
pandas
numpy
seaborn
matplotlib

# How to Use
Clone the repository.
Install the required dependencies using pip install -r requirements.txt.
Run the Jupyter notebook or Python script to reproduce the analysis and results.
Contributing
Feel free to contribute by forking the repository and creating pull requests. Bug reports, suggestions, and improvements are welcome!

# License
This project is licensed under the MIT License.

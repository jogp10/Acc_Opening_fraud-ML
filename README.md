# Project Overview
This project aims to provide a brief introduction to the project, its purpose, and its main goals. It addresses the problem of [describe the problem or task being tackled with machine learning]. The goal is to [explain the desired outcome or objective].

# Prerequisites
To run the Jupyter Notebook, you need the following software dependencies:
- Python (version 3.10)
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Tabulate
- imblearn

To install the dependencies, follow these steps:
1. Install Python from [Python website](https://www.python.org/downloads/).
2. Install Jupyter Notebook using the command: `pip install jupyter notebook`.
3. Install other required packages using the command: `pip install -r requirements.txt`.

# Dataset Description
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022). It is in CSV. The dataset contains 31 features, for example income, age, fraud_bool, name_email_similarity, and the target variable is 'fraud_bool' indicating if an account opening is fraudulent or not.

Preprocessing steps performed on the dataset include removing column with only one single value, normalizing features, encoding categorical ones, strongly correlated features selection.

# Notebook Structure
The Jupyter Notebook is structured as follows:

1. Project Description
2. Data Understanding and Exploration (visualize dataset, address outliers, target variable distribution, division of variables, etc)
3. Exploratory Data Analysis (EDA) (plots and statistics to understand relations between variables and target variable and also between variables)
4. Feature Engineering and Selection (data encoding, selection of relevant features, analysing dataset imbalance recurring to ROC curves)
5. Datasets preparation for the models (splitting processed dataset into training and testing sets)
6. Statistical Modeling (applying modeling techniques)
7. Models Evaluation and Validation (analyse models performance on testing data, fine-tuning and applying cross validation techniques)
8. Interpretation and Conclusions


# Usage Instructions
To run the Jupyter Notebook and reproduce the results, follow these steps:

1. Install the required dependencies as mentioned in the "Prerequisites" section.
2. Download the notebook file and the dataset.
3. Open the Jupyter Notebook using the command: `jupyter notebook`.
4. Navigate to the directory where the notebook file is located.
5. Open the notebook and execute the cells one by one.
6. Make any necessary modifications or provide inputs as instructed in the notebook.
7. Follow the step-by-step instructions within the notebook to reproduce the results.

# Model Evaluation
The performance of the machine learning models was evaluated using ROC curves, recall score among others.

# References
- [Dataset](https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022)
- [Dataset detailed information](https://github.com/feedzai/bank-account-fraud/blob/main/documents/datasheet.pdf)
- [NeurIPS 2022 paper](https://arxiv.org/abs/2211.13358)

# Author Information
João Pinheiro (202008133)

José Araújo (202007921)

Ricardo Cavalheiro (202005103)
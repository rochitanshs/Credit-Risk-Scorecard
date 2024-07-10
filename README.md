# Credit Risk Model and Scorecard Development

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Project Structure](#project-structure)
7. [Methodology](#methodology)
8. [Results](#results)
9. [Contributing](#contributing)
10. [License](#license)
11. [Contact](#contact)

## Project Overview

This project develops a comprehensive credit risk model and scorecard using machine learning techniques, following industry standards for banking and lending. It utilizes loan data from 2015 to predict the probability of loan default and create a credit scoring system.

## Features

- Data exploration and visualization
- Advanced data cleaning and preprocessing
- Feature selection and engineering
- Implementation of multiple machine learning models:
  - XGBoost
  - Logistic Regression
  - Random Forest
- Model performance comparison
- Credit scorecard development
- Visualization of results

## Requirements

- Python 3.7+
- pandas
- numpy      
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Installation

1. Clone the repository: git clone https://github.com/rochitanshs/credit-risk-model.git
2. Navigate to the project directory: cd credit-risk-model
3. Install required packages: pip install -r requirements.txt

For detailed usage of individual components, refer to the documentation in each module.

## Project Structure

- `credit-risk-model/`
  - `data/`
    - `loan_data_2015.csv`
  - `notebooks/`
    - `credit_risk_model_development.ipynb`
  - `src/`
    - `data_preparation.py`
    - `feature_engineering.py`
    - `model_training.py`
    - `scorecard_development.py`
  - `README.md`
  - `requirements.txt`
  - `main.py`
## Methodology

1. **Data Import and Exploration**
   - Load and examine the structure of the loan data
   - Perform exploratory data analysis (EDA)

2. **Data Cleaning and Preprocessing**
   - Handle missing values
   - Treat outliers
   - Encode categorical variables

3. **Feature Selection and Engineering**
   - Correlation analysis
   - Weight of Evidence (WoE) transformation
   - Information Value (IV) calculation

4. **Model Development**
   - Train and evaluate multiple models:
     - XGBoost
     - Logistic Regression
     - Random Forest

5. **Model Evaluation and Comparison**
   - Use metrics such as AUC-ROC, precision, recall, and F1-score
   - Analyze feature importances

6. **Scorecard Creation**
   - Develop a credit scorecard based on the best-performing model
   - Scale scores to a standard range (e.g., 300-850)

## Results

(This section will be updated with actual results after running the models)

Example metrics to be included:
- Model comparison table (AUC-ROC, precision, recall for each model)
- Feature importance rankings
- Distribution of credit scores in the test set

## Contributing

We welcome contributions to improve the project. Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Rochitansh Singh - www.linkedin.com/in/rochitanshsingh - rochitansh@gmail.com

Project Link: [https://github.com/rochitashs/credit-risk-model](https://github.com/rochitanshs/credit-risk-model)

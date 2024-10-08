# Credit Risk Scoring Project

## Project Overview
This project implements and compares multiple approaches to credit risk scoring using the German Credit Dataset. It explores traditional statistical methods to predict credit risk, focusing on linear and logistic regression models.

## Key Features
- Comprehensive data preprocessing and exploratory data analysis
- Implementation of four different models:
  - Linear Regression (for Checking = 1 or 2)
  - Logistic Regression (for Checking = 1 or 2)
  - Linear Regression (for Checking = 3 or 4)
  - Logistic Regression (for Checking = 3 or 4)
- Comparative analysis of model performance
- Use of various financial attributes as predictive features

## Data
The project uses the German Credit Dataset, which contains information on 1000 loan applicants, including various attributes and whether they were considered good or bad credit risks.

## Methodology
1. Data Preprocessing:
   - Splitting dataset based on 'Checking' account status
   - Handling missing values and outliers
   - Feature engineering and selection

2. Exploratory Data Analysis:
   - Distribution analysis of features
   - Correlation analysis
   - Visualization of key relationships

3. Model Implementation:
   - Linear and Logistic Regression models for both subsets

4. Feature Selection and Engineering:
   - Information Value (IV) calculation
   - Optimal binning of continuous variables
   - One-hot encoding of categorical variables

5. Model Evaluation:
   - ROC curve analysis
   - Gini coefficient calculation
   - Kolmogorov-Smirnov (KS) statistic

## Results
The performance metrics for each model are as follows:

| Model | Dataset | AUC | Gini Coefficient | KS Value |
|-------|---------|-----|------------------|----------|
| Linear Regression | Checking = 1 or 2 | 0.634 | 0.269 | 0.229 |
| Logistic Regression | Checking = 1 or 2 | 0.629 | 0.258 | 0.228 |
| Linear Regression | Checking = 3 or 4 | 0.645 | 0.290 | 0.325 |
| Logistic Regression | Checking = 3 or 4 | 0.645 | 0.289 | 0.314 |

The models show moderate discriminative power, with slightly better performance for the Checking = 3 or 4 subset. The linear and logistic regression models perform similarly within each subset.

## Repository Structure
- `data/`: Contains the dataset
- `code/`: Jupyter notebook for data analysis and model implementation
- `report/`: Full report

## Usage
1. Clone the repository
2. Run the Jupyter notebooks in the `code/` directory for step-by-step analysis and model implementation

## Future Work
- Exploration of more advanced machine learning techniques
- Integration of alternative data sources
- Development of a more comprehensive credit scoring system

## Contributors
- Eshaq Rahmani

## Acknowledgments
- The creators and maintainers of the German Credit Dataset
- The scikit-learn development team for their excellent library

# Credit Risk Scoring Project

## Project Overview
This project implements and compares multiple approaches to credit risk scoring using the German Credit Dataset. It explores traditional statistical methods and machine learning techniques to predict credit risk.

## Key Features
- Data preprocessing and exploratory data analysis
- Implementation of four different models:
  - Linear Regression
  - Logistic Regression
  - Long Short-Term Memory (LSTM)
  - Convolutional Neural Network (CNN)
- Comparative analysis of model performance
- Use of various technical indicators and financial ratios as predictive features

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
   - Linear and Logistic Regression models
   - LSTM and CNN models for more complex pattern recognition

4. Feature Selection and Engineering:
   - Information Value (IV) calculation
   - Optimal binning of continuous variables
   - One-hot encoding of categorical variables

5. Model Evaluation:
   - ROC curve analysis
   - Gini coefficient calculation
   - Kolmogorov-Smirnov (KS) statistic

## Results
The project provides a comprehensive comparison of different credit scoring models, highlighting their strengths and limitations in predicting credit risk.

## Repository Structure
- `data/`: Contains the dataset and data preparation scripts
- `notebooks/`: Jupyter notebooks for data analysis and model implementation
- `src/`: Source code for model implementations and utilities
- `results/`: Output files, figures, and detailed result analysis
- `requirements.txt`: List of required Python packages

## Usage
1. Clone the repository
2. Install the required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebooks in the `notebooks/` directory for step-by-step analysis and model implementation

## Future Work
- Exploration of more advanced machine learning techniques
- Integration of alternative data sources
- Development of a more comprehensive credit scoring system

## Contributors
- Eshaq Rahmani
  
## Acknowledgments
- The creators and maintainers of the German Credit Dataset
- The scikit-learn, TensorFlow, and Keras development teams for their excellent libraries

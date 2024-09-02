# Comprehensive Credit Score Analysis and Predictive Modeling

## Project Overview

This project involves the analysis and predictive modeling of a large credit score dataset containing over 100,000 rows and 25+ columns. The goal was to uncover insights into customer credit behavior and develop a model capable of accurately predicting credit scores. The project included extensive data cleaning, exploratory data analysis (EDA), feature engineering, and model development.

## Dataset Description

The dataset used in this project includes various features related to customers' financial history, credit behavior, and personal details. Some key features include Annual Income, Age, Number of Loans, Outstanding Debt, Monthly Balance, and more.

## Data Preprocessing

### 1. Handling Missing Values
- Missing values in critical columns were identified and addressed using appropriate imputation techniques.
- Categorical and numerical features were treated differently, ensuring that the dataset remained robust for further analysis.

### 2. Data Cleaning
- Features containing strings were split and converted to numeric types where applicable.
- Special characters and erroneous entries were removed, particularly in columns like `Changed_Credit_Limit` and `Payment_Behaviour`.

### 3. Data Type Conversion
- Several columns initially read as strings were converted to numeric types to facilitate analysis. This included columns like `Annual_Income`, `Age`, and `Num_of_Loan`.

## Exploratory Data Analysis (EDA)

### 1. Visualizations
- Various visualizations were created using Matplotlib and Seaborn to explore the distribution of features, relationships between variables, and patterns in the data.
- Histograms, box plots, and scatter plots were used to identify outliers, skewness, and correlations.

### 2. Statistical Analysis
- Descriptive statistics were generated to summarize the central tendency, dispersion, and shape of the dataset’s distribution.
- Correlation matrices were used to examine relationships between variables, guiding feature selection and engineering.

## Feature Engineering

### 1. Feature Transformation
- Transformations such as splitting strings, replacing special characters, and normalizing data were applied to prepare features for modeling.
- Feature selection techniques like Principal Component Analysis (PCA) were employed to reduce dimensionality while retaining important information.

### 2. Creating New Features
- New features were engineered based on existing ones to enhance model performance. This included interaction terms and polynomial features where relevant.

## Modeling

### 1. Model Development
- Multiple predictive models were developed and evaluated, including decision trees, random forests, and gradient boosting machines.
- Hyperparameter tuning was performed to optimize model performance.

### 2. Model Evaluation
- Models were evaluated using metrics such as accuracy, precision, recall, and F1-score.
- The final model achieved a 76% accuracy in predicting credit scores, demonstrating the effectiveness of the preprocessing and feature engineering steps.

## Results

- The final model was able to predict credit scores with an accuracy of 76%, indicating strong predictive power given the complexity of the dataset.
- The insights gained from the EDA and feature engineering steps were crucial in enhancing model performance and understanding customer credit behavior.

## Conclusion

This project successfully developed a robust predictive model for credit scores, leveraging advanced data preprocessing, feature engineering, and modeling techniques. The detailed analysis provided valuable insights into customer credit behavior, which could be used for further financial analysis or decision-making processes.

## How to Run the Code

1. **Clone the repository:**
   ```bash
   git clone <repository_url>

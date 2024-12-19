<<<<<<< HEAD
# GlucoSense_Infosys_Internship_Nov2024
=======


# Diabetes Prediction - Exploratory Data Analysis (EDA)

This project focuses on performing Exploratory Data Analysis (EDA) on a diabetes prediction dataset. The objective of this analysis is to uncover key patterns, correlations, and insights from the data, which can later help in building predictive models for diabetes classification.

## Project Overview

The dataset contains various attributes related to patients' health, including both symptoms and demographic features, which are used to predict whether a person has diabetes or not.

In this EDA, we explore various aspects of the dataset such as:

- **Age Distribution:** Examining the spread of ages within the dataset and its relationship with diabetes.
- **Correlation Analysis:** Investigating relationships between features and the target variable (diabetes class).
- **Symptoms Distribution:** Analyzing the occurrence of various symptoms, including polyuria, polydipsia, weakness, obesity, and others, by diabetes class.
- **Feature Relationships:** Understanding how different features correlate with one another and how they relate to diabetes.

## Dataset

- **Age**: Age of the individual
- **Gender**: Gender of the individual
- **Polyuria**: Frequent urination
- **Polydipsia**: Excessive thirst
- **Weakness**: Weakness or fatigue
- **Obesity**: Body mass index (BMI) categorization
- **Sudden Weight Loss**: Unexpected weight loss
- **Muscle Stiffness**: Presence of muscle stiffness
- **Genital Thrush**: Presence of fungal infection
- **Class**: Diabetes classification (Positive/Negative)

## Key Insights

- **Age Group Distribution:** Diabetic cases are more prevalent among individuals aged 40-70. There is a higher occurrence of diabetes in the middle-aged and elderly groups.
- **Symptoms Analysis:** Certain symptoms like polyuria and polydipsia have strong correlations with diabetes, making them valuable predictors.
- **Feature Correlation:** Age, obesity, and certain symptoms show varying degrees of correlation with the diabetes class. Age, in particular, shows weaker correlation with the target, suggesting that other features may be more important predictors.
- **Class Imbalance:** A significant imbalance exists between the diabetic (Positive) and non-diabetic (Negative) classes, which may need to be addressed in future modeling steps.

## Visualizations

This project uses the following visualizations to better understand the dataset:

- **Histograms**: To analyze the distribution of continuous features like age.
- **Countplots**: To examine the frequency of categorical features like class, gender, and symptoms.
- **Boxplots**: To visualize the spread of numerical features across different classes.
- **Correlation Heatmaps**: To identify relationships between numerical features and their correlation with the target variable.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction-eda.git
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook to view the EDA:
   ```bash
   jupyter notebook
   ```

## Future Work

- Address class imbalance using oversampling or undersampling techniques.
- Build machine learning models (e.g., Logistic Regression, Decision Trees) to predict diabetes based on the features.
- Hyperparameter tuning for the chosen model to optimize performance.
  


>>>>>>> 0c731ab (files added)

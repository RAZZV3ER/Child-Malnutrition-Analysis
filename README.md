# Child Malnutrition Analysis

This repository contains:

- **Notebooks** for data loading, cleaning, and analysis.
- **Processed data** in `data/processed_and_cleaned/`.
- **Reports** in `reports/`.

Dataset: JME_Country_Estimates_April_2021 (UNICEF)

This project analyzes child malnutrition indicators (Stunting, Wasting, Overweight, Underweight) using country-level survey data from UNICEF and WHO. The goal is to predict malnutrition levels based on demographic and regional factors, helping identify high-risk regions. The workflow includes data cleaning, exploratory analysis, feature engineering, and predictive modeling using machine learning techniques like Random Forest, SVM, and ensemble methods.

# Description of Features inside the dataset

- **Stunting:** Percentage of children under 5 who are shorter than the normal height for their age. Indicates chronic malnutrition.

- **Wasting:** Percentage of children under 5 who are thinner than the normal weight for their height. Indicates acute malnutrition.

- **Overweight:** Percentage of children under 5 who are heavier than the normal weight for their height. Indicates overnutrition.

- **Underweight:** Percentage of children under 5 who weigh less than the normal weight for their age. Reflects both chronic and acute malnutrition.

- **U5_Population:** Number of children under 5 years old (in thousands). Provides context for malnutrition percentages.


*These features can be used either as predictors or target variables for machine learning models, depending on the analysis goal.*

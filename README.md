# Relax Inc. Take-Home Challenge: User Adoption Analysis

## Project Overview

This project analyzes user data to identify factors associated with user adoption for Relax Inc.

An adopted user is defined as someone who logged into the product on at least three separate days within any seven-day period.

## Objectives

* Explore user account and engagement data.
* Identify factors associated with user adoption.
* Perform exploratory data analysis (EDA).
* Build and evaluate classification models.

## Dataset

The project uses two datasets provided with the challenge:

* User account information
* User engagement login records

**Note:** The original datasets are not included in this repository because they contain personal information.

## Tools and Techniques

* Python and Pandas
* Matplotlib and Seaborn
* Scikit-learn
* Exploratory Data Analysis
* Logistic Regression
* Random Forest
* Model evaluation using precision, recall, F1-score, ROC-AUC, and confusion matrix

## Key Findings

* The dataset contained 12,000 users.
* A total of 1,602 users met the adopted-user definition, giving an adoption rate of 13.35%.
* Signup source and invitation status showed differences in adoption rates.
* Users in smaller organizations had a higher observed adoption rate than users in larger organizations.
* Logistic Regression performed better than Random Forest at identifying adopted users, although its precision was low.
* A baseline model achieved 86.67% accuracy by predicting every user as non-adopted, but it failed to identify any adopted users.

## Conclusion

The analysis identified several characteristics associated with user adoption. Further feature engineering, model tuning, and validation are needed before using the model for business decisions. These findings indicate associations, not causation.

## Project File

* `Relax_Adopted_User_Analysis.ipynb` — Jupyter Notebook containing the analysis, visualizations, and modeling.

## Reproducibility

To run the notebook, place the original challenge CSV files in a local folder named `relax_challenge`, using the filenames expected by the notebook. Install the required Python libraries and run the notebook from top to bottom.

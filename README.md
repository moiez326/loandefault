![Loan Default](https://www.lendingtree.com/content/uploads/2020/01/mortgage-default.jpg)
# Loan Default Prediction for Global Bank

## Project Overview
This project focuses on developing a machine-learning model to predict loan defaults for Global Bank (GB). The goal is to enhance GB's loan approval process by identifying critical features that impact loan defaults and improving risk assessment accuracy.

### Data Source
Information on 5,960 home equity loans and includes various attributes such as loan amount, mortgage information, applicant demographics, and loan outcomes (default or repayment).

## Key Insights
- **Default Prediction**: We aim to build a binary classification model to predict loan defaults (DL) and minimize false negatives (clients predicted as GL but turn out to be DL).
- **Exploratory Data Analysis (EDA)**: The analysis of the dataset revealed valuable insights, such as the significance of financial metrics, correlations between loan attributes, and differences in loan default rates for various reasons and job types.

## Analysis Highlights

1. **Data Cleaning and Preprocessing**: The dataset underwent cleaning, standardization, and handling of missing values to prepare it for analysis.
2. **EDA**: Exploratory Data Analysis provided insights into the distribution of financial metrics, correlations between variables, and patterns in loan defaults based on reasons and job types.

![EDA Chart](insert_eda_chart_url_here)

3. **Model Development**: Machine-learning models were trained and evaluated to predict loan defaults accurately.

## Analysis Summary and Key Findings

- Loan amount was not a significant indicator of clients defaulting.
![Chart 1](https://github.com/moiez326/loandefault/blob/main/media/Screenshot%202023-11-28%20at%2013.36.39.png)
- Credit-related variables such as derogatory reports showed a more drastic difference in frequency of bad and good loan status.
![Chart 2](https://github.com/moiez326/loandefault/blob/main/media/Screenshot%202023-11-28%20at%2013.37.35.png)

## Conclusions

The analysis suggests that while discounts are a common strategy, they do not significantly alter customer ratings. This could imply that product quality and brand reputation might play more substantial roles in customer satisfaction than pricing strategies alone.

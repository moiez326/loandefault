# Discount Strategy and Customer Ratings Analysis

## Overview

This repository contains an analysis focused on understanding the impact of discount strategies on customer ratings for two leading sports apparel companies: Adidas and Nike. The goal is to derive insights into how discounts influence customer perceptions and to identify patterns that could inform future pricing strategies.

### Data Source

The analysis is based on a dataset (`cleaned_loan.csv`) containing detailed information on discounts and customer ratings, among other variables.

### Tools & Technologies

- Python for data analysis and manipulation.
- Seaborn and Matplotlib for visualization.
- Jupyter Notebook for interactive development and documentation.

## Analysis Summary

- The lines of best fit for both Adidas and Nike are relatively flat, suggesting that discounts do not have a strong linear impact on customer ratings.
- The majority of customer ratings are concentrated between 3.0 and 5.0, indicating a high level of satisfaction irrespective of the discount received.
- A noticeable difference in discount ranges between the two brands, with Adidas offering discounts up to 60%, while Nike up to 30%, indicating a broader discount strategy by Adidas.

## Repository Structure

- `loan_EDA.ipynb`: The Jupyter notebook containing the exploratory data analysis and visualization code.
- `cleaned_loan.csv`: The preprocessed dataset used for the analysis.
- `README.md`: Provides an overview and findings of the project.

## Key Findings

- Discounts seem to have a minimal effect on how customers rate their purchases for both Adidas and Nike.
- Customer satisfaction remains consistently high across different levels of discounting.
- Adidas tends to offer larger discounts compared to Nike, which could suggest different marketing strategies or customer base expectations.

## Visualizations

The repository includes visualizations that compare discounts to customer ratings, such as:

- Scatter plots with transparency to handle overplotting.
- Lines of best fit to gauge trends and relationships.
- Distribution plots to visualize the range and concentration of discounts and ratings.

## Conclusions

The analysis suggests that while discounts are a common strategy, they do not significantly alter customer ratings. This could imply that product quality and brand reputation might play more substantial roles in customer satisfaction than pricing strategies alone.

## Future Work

Further analysis could involve:

- Segmenting the data by product type to understand if certain categories are more sensitive to discounts.
- Time-series analysis to explore seasonal effects on discounts and ratings.
- Customer demographic analysis to tailor discount strategies to specific customer segments.

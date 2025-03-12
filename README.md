# Comprehensive Consumer Behavior Analysis Enriched by Google Trends

## Project Proposal

This project aims to analyze comprehensive consumer behavior data to uncover key insights into customer demographics, purchase behaviors, product preferences, and decision-making processes. The project will further enrich this analysis using external trend data from Google Trends to better understand how online search behaviors influence consumer purchasing decisions.

## Data to be Used

- **Primary Data**: "Comprehensive Consumer Behavior" dataset from Kaggle, including demographic information, purchase details, customer satisfaction, and product feedback.
- **Secondary Data (Google Trends)**: Search volume data for selected product categories obtained via Google Trends.

## Plans for Data Collection

- The primary dataset will be downloaded directly from Kaggle as a CSV file.
- Google Trends data will be collected using the `pytrends` Python library, focusing on specific product categories relevant to the primary dataset.
- Data will be aligned temporally and aggregated appropriately (weekly or monthly) to facilitate meaningful analysis.

## Hypothesis

### Hypothesis 1: Relationship between Google Trends search popularity and consumer purchase amounts

- **Null Hypothesis (H0)**: There is no significant relationship between Google Trends search volume for product categories and consumer purchase amounts.  
  *(ρ = 0)*

- **Alternative Hypothesis (H1)**: There is a significant relationship between Google Trends search volume for product categories and consumer purchase amounts.  
  *(ρ ≠ 0)*


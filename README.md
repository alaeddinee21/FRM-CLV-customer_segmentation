---
here is the datalink :https://www.kaggle.com/code/shailaja4247/customer-lifetime-value-prediction/input

# Customer Profiling Using RFM and CLV

This repository showcases a comprehensive approach to customer profiling by integrating RFM (Recency, Frequency, Monetary) analysis and Customer Lifetime Value (CLV) estimation. The project is structured to provide valuable insights into customer behavior, facilitating data-driven marketing strategies.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Features](#features)
- [Data Description](#data-description)
- [Installation](#installation)
- [Technology Stack](#technology-stack)
- [Methodology](#methodology)
- [Analysis and Insights](#analysis-and-insights)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to analyze and segment customers using a dual approach that evaluates both short-term engagement through RFM analysis and long-term value through CLV estimation. This holistic profiling enables businesses to optimize their marketing efforts and enhance customer retention.

## Project Structure
The project is organized as follows:

### Analysis
- **Monthly Active Customers:** Tracking the number of active customers each month.
- **Average Revenue per Order:** Calculating the average revenue generated per order.
- **New Customer Ratio:** Assessing the ratio of new customers acquired each month.
- **Monthly Retention Rate:** Analyzing the retention rate of customers on a monthly basis.

### Customer Segmentation
- **RFM Segmentation:**
  - **Recency:** Number of days since the last purchase.
  - **Frequency:** Total number of purchases made.
  - **Monetary:** Total amount spent by the customer.
  - **Overall Score:** Combined RFM score for segmentation.
  - **Skewness:** Assessing the distribution of RFM scores.
  - **Jarque-Bera Test Results:** Statistical test for normality of RFM data.
  - **Kruskal-Wallis H Test:** Non-parametric test to compare RFM distributions across different customer segments.

### Customer Lifetime Value
- **Algorithm Comparison:** Evaluation of different algorithms to calculate CLV and determine the most accurate prediction model.

### Overall Marketing Insight
- Combining the insights from RFM and CLV analysis to provide actionable recommendations for marketing strategies.

## Features
- **Comprehensive Customer Analysis:** Provides detailed insights into customer behavior and value.
- **RFM and CLV Integration:** Combines short-term and long-term customer behavior for robust profiling.
- **Advanced Statistical Tests:** Includes skewness, Jarque-Bera, and Kruskal-Wallis tests for rigorous analysis.
- **Algorithm Comparison for CLV:** Compares different models to find the most effective method for estimating customer lifetime value.

## Data Description
The dataset used in this project includes:
- **Customer ID:** Unique identifier for each customer.
- **Transaction Date:** Date of each transaction.
- **Purchase Amount:** The monetary value of each transaction.

These data points are essential for calculating RFM scores and estimating CLV.

## Installation
To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Customer-Profiling.git
   cd Customer-Profiling
   ```

3. **Run the notebook:**
   ```bash
   jupyter notebook
   ```

## Technology Stack
This project utilizes the following technologies:
- **Python:** Core programming language for data analysis and modeling.
- **Pandas:** Used for data manipulation and analysis.
- **NumPy:** Utilized for numerical computations.
- **Matplotlib & Seaborn:** Libraries for data visualization.
- **SciPy:** Used for statistical tests like Jarque-Bera and Kruskal-Wallis.
- **Scikit-learn:** Applied for clustering and model comparison in CLV estimation.
- **Jupyter Notebook:** Interactive environment for running the analysis and visualizations.

## Methodology
### RFM Analysis
- **Recency, Frequency, Monetary:** Calculated for each customer to segment them into meaningful groups.
- **Statistical Tests:** Skewness, Jarque-Bera, and Kruskal-Wallis tests applied to assess data distribution and segment differences.

### CLV Calculation
- **Algorithm Comparison:** Different models evaluated to estimate customer lifetime value accurately.

### Combined Insights
- **Cross-analysis of RFM and CLV:** Provides a comprehensive view of customer behavior, integrating both short-term engagement and long-term value.

## Analysis and Insights
This project provides a detailed breakdown of customer behavior, including active customer trends, revenue analysis, customer segmentation, and lifetime value predictions. The insights gained are crucial for refining marketing strategies and improving customer retention.

## Results
### Overall Marketing Insight:
- **Strong Performance**: The model performs well in predicting customer segments, particularly for the Mid-Value group.
- **Precision & Targeting**: High precision (0.89) means that marketing campaigns can confidently target the predicted customer segments without much risk of misclassification.
- **Actionable Strategies**:
  - For **High-Value customers**, personalized loyalty programs can be implemented with confidence.
  - The **Mid-Value segment** is well-classified and can be targeted for upselling or engagement strategies.
  - The **Low-Value segment** shows some misclassifications, meaning you might need to revisit the features or consider other variables to better identify these customers for retention campaigns.
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
---

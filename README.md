# Marketing Analysis

## Overview

This project analyzes customer data to uncover key insights into purchasing behavior, campaign effectiveness, and customer segmentation. Using Python and Matplotlib, the analysis explores how different customer attributes and behaviors influence marketing outcomes.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Feature Description](#feature-description)
- [Project Workflow](#project-workflow)
- [Key Findings](#key-findings)
- [Conclusion](#conclusion)

---

## Dataset

- **Source:** [Specify the source, e.g., internal company data or a public dataset]
- **Contents:** Demographics, purchase history, campaign responses, and online/offline shopping behavior.

---

## Feature Description

| Feature               | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| AcceptedCmp1-5        | 1 if customer accepted offer in campaign 1-5, 0 otherwise                   |
| Response (target)     | 1 if customer accepted the last campaign, 0 otherwise                       |
| Complain              | 1 if customer complained in last 2 years                                    |
| DtCustomer            | Date of enrollment with the company                                         |
| Education             | Customer's level of education                                               |
| Marital               | Marital status                                                              |
| Kidhome/Teenhome      | Number of small children/teenagers in household                             |
| Income                | Yearly household income                                                     |
| MntFish/Meat/Fruits/Sweet/Wines/GoldProds | Amount spent on each product category in last 2 years   |
| NumDealsPurchases     | Number of purchases with discount                                           |
| NumCatalogPurchases   | Purchases made using catalogue                                              |
| NumStorePurchases     | Purchases made in store                                                     |
| NumWebPurchases       | Purchases made through website                                              |
| NumWebVisitsMonth     | Number of website visits in last month                                      |
| Recency               | Days since last purchase                                                    |

---

## Project Workflow

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Outlier Detection and Handling
- Correlation Analysis
- Campaign Success Evaluation
- Customer Segmentation (clustering in a separate notebook)

---

## Key Findings

- **Income Distribution:** Customers have a wide range of incomes, indicating both high- and low-income segments.
- **Spending Patterns:** Preferences vary across product categories, with some customers favoring wines, others fruits, meat, or fish.
- **Outlier Detection:** Significant outliers exist in income and spending, requiring careful preprocessing.
- **Acceptance Rate:** Overall campaign acceptance was low, with most customers not responding positively to promotions.
- **Campaign Success:** The first campaign (AcceptedCmp1) had the highest success rate, suggesting greater receptivity to initial offers.
- **Correlation Analysis:** Wine spending, regular product purchases, and income showed the strongest positive correlation with campaign acceptance. Households with children or teenagers were less likely to accept offers.



---

## Conclusion

The analysis reveals that customer purchasing behavior and campaign responsiveness are influenced by income, product preferences, and household composition. Initial campaigns tend to perform better, and targeted strategies should focus on high-value segments such as frequent wine buyers and higher-income customers. Households with children and teenagers are less responsive, suggesting the need for differentiated marketing approaches.


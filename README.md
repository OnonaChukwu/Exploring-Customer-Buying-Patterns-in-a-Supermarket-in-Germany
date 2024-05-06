# Exploring Customer Buying Patterns in a Supermarket in Germany
![image](https://github.com/OnonaChukwu/Supermarket_sales/assets/155753951/866ba920-f0d1-4e49-9d6b-e49526281589)

## Executive Summary
This case study explores the relationship between customer demographics, membership status, and purchasing behaviour in a supermarket setting. Using data visualization and statistical modeling, the study aims to identify key customer segments and understand their spending patterns. The insights gained could help the supermarket tailor marketing strategies to increase customer engagement and optimize sales efforts.

## Introduction and Background
- Overview of the retail industry and the importance of customer segmentation is crucial.
- Brief description of the supermarket's business model and customer base can make planning easy.
- Dataset was generated in Jupiter based on real life ranges, in line with supermarket feasibilities.

## Challenge and Motivation
- There is a srong need to understand diverse customer behaviours to tailor marketing and sales strategies effectively.
- Challenges in predicting customer spending based on demographics and membership status need to be tackled through a data-driven approach.
- Importance of optimizing stock levels and marketing to enhance customer satisfaction and loyalty are essential for maximising profit.

## Aim and Objectives
- To identify patterns and trends in customer spending.
- To explore the impact of customer demographics and membership status on purchase behaviours.
- To develop predictive models to estimate customer spending based on given attributes.

## Hypothesis and Research
- Hypothesis: Membership status and specific demographics significantly influence customer spending patterns.
- Research focus on validating the hypothesis through statistical analysis and model development.

## Methodology
- Data cleaning including handling missing values and outliers were carried out in Excel and Python Jupiter.
- Exploratory data analysis using statistical summaries and visualizations were conducted to search for insights.
- Segmentation analysis to identify high-value customers were also conducted appropriately in the dataset.
- Linear regression modelling to predict purchase amounts based on customer demographics were conducted.

## Results and Interpretations

**Who are the most valuable customers?**
![image](https://github.com/OnonaChukwu/Supermarket_sales/assets/155753951/46f2a305-72d4-4b41-ba8e-89a5396eb694)
- The top 10% of customers by spending score and purchase amount have higher incomes and distinct membership statuses.
- These high-value customers are evenly distributed across all membership statuses, but a notable portion are "Platinum" members.
- This means that while membership status contributes to high spending, income and other factors also play significant roles. 

**How does customer behavior vary by demographic factors?**
![image](https://github.com/OnonaChukwu/Supermarket_sales/assets/155753951/d6262208-51fe-4f43-ae13-40e99293cece)
- Spending trends reveal that the older age groups (46-55 and 56-65) tend to spend more on average compared to younger groups.
- This could indicate that middle-aged to older customers have more disposable income, or have finished paying for mortgages, and are less bordered by bills.
- The male customers in the 36-45 age group spend significantly more than their female counterparts.
- This suggests that targeted marketing might be effective for this demographic.

**What is the relationship between annual income and spending score?**
- The correlation coefficient of **0.5** suggests a moderately strong positive relationship between spending score and annual income.
- The higher the annual income of the customer, the higher the customers spending income 

**Which product categories are most popular among different membership statuses?**
![image](https://github.com/OnonaChukwu/Supermarket_sales/assets/155753951/48b5d81e-d424-467e-aa9e-a7ee4bf7e7df)
- The electronics and clothing are more popular among Platinum members, while Groceries are preferred by Silver members.
- This suggests that premium membership status (Platinum) might influence the purchase of higher-value items, which can be leveraged in upselling strategies.

**How effective is the membership status in encouraging more store visits or higher spending?**
![image](https://github.com/OnonaChukwu/Supermarket_sales/assets/155753951/09a1608e-5d56-49dd-9f2e-2d32e3e0688a)
- Gold members visit the store more frequently and spend more on average compared to Silver and Platinum members.
- Exactly, these Gold members visit the store about 20% more frequently and spend approximately 15% more than Silver members.
- These show the success of the Gold membership in fostering customer loyalty and frequent spending.
- It actually suggests that enhancing the benefits of this tier could further increase these metrics.

**Can we predict future purchase behavior based on available data?**
![image](https://github.com/OnonaChukwu/Supermarket_sales/assets/155753951/5ad4fea4-e474-4f67-8d5e-bcb887f59fe8)
- Model performance assessment reveals that the predictive model displayed a good fit, as indicated by a cluster of data points around the line of perfect prediction (45-degree line in the plot).
- In the context of practical use, the model's ability to predict purchase amounts based on age, income, and spending score can be utilized to forecast future sales and to tailor offers to individual customer's predicted spending levels.
- The supermarket can always reliably leverage on this.

## Conclusions
- Membership status is a strong indicator of purchase behaviour.
- High-income customers tend to have higher spending scores and contribute significantly to sales.
- Predictive modelling can be effectively used to estimate purchase amounts and guide marketing strategies.

## Recommendations
- Enhance membership benefits to convert more customers into higher status tiers.
- Target high-income customer segments with tailored marketing campaigns.
- Continuously refine predictive models using new data to improve accuracy.

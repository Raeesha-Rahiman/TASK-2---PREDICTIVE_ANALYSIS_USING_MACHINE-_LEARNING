# TASK-2 PREDICTIVE_ANALYSIS_USING_MACHINE_LEARNING

COMPANY :CODTECH IT SOLUTIONS

NAME: RAEESHA RAHIMAN

INTERN ID : CTIS9280

DOMAIN : DATA ANALYTICS

DURATION : 4WEEKS

MENTOR : NEELA SANTOSH KUMAR

# Predictive Profit Analysis & Customer Behavioral Analytics
### Project Overview

This project focuses on predictive analysis using the Superstore dataset to understand the factors affecting company profit and customer behavior.
The dataset was initially explored using SQL and connected through SQLAlchemy engine for data extraction and analysis. The project combines business understanding, exploratory data analysis, machine learning, and business recommendations to identify how discounts, sales, and customer behavior impact profitability.

## Business Problem

During exploratory data analysis, it was identified that discount had the strongest negative relationship with profit.
Some high-sales transactions were still generating losses due to excessive discounts, especially in the Furniture category.

The project aimed to answer:

Are discounts actually hurting profit?
Can profit be predicted using business features?
Can customer value be predicted using only behavioral patterns?

## Dataset Description

- Row ID
- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Postal Code
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

To improve data understanding and analytical structure, a Star Schema data model was created from the original transactional table.
The following tables were designed:

 - Sales Fact Table
 - Product Dimension Table
 - Customer Dimension Table

This helped organize the data for better analysis, reporting, and machine learning workflows.

## Technologies & Tools Used
- Python
- SQL
- SQLAlchemy Engine
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
- Data Collection using SQL and Python
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Selection
- Train-Test Splitting
- Model Building
- Prediction & Evaluation
- Business Insights & Recommendations

## Predictive Analysis Performed
### Regression Analysis

Regression analysis was performed to predict profit using features such as sales, quantity, discount, category, region, and ship mode.
A Random Forest Regressor model was trained to analyze how discounts and other business components affect profitability.

The analysis showed that higher discounts consistently reduce profit and can eventually turn profitable sales into losses.
DETAILES OF PROJECT :- 
    https://github.com/Raeesha-Rahiman/TASK-2---PREDICTIVE_ANALYSIS_USING_MACHINE-_LEARNING/blob/main/A%20Regression%20Predictive%20Analysis%20journey.pdf

### Classification Predictive Analysis

Classification analysis was performed to classify customer value and customer behavior using features related to sales, profit, quantity, discount, and purchase behavior.

The objective was to identify whether customer purchasing patterns and financial contribution could help classify valuable customers.

The analysis demonstrated that customer behavior and transaction patterns can provide meaningful insights for customer segmentation, targeting, and business strategy improvement.
To know story of analysis :-  
    https://github.com/Raeesha-Rahiman/TASK-2---PREDICTIVE_ANALYSIS_USING_MACHINE-_LEARNING/blob/main/Customer_Value_Classification_Story.pdf

### Conclusion

This project successfully demonstrated how predictive analytics can help businesses understand profitability and customer behavior.

The analysis confirmed that excessive discounting is one of the major reasons for profit loss, especially in the Furniture category. The project also showed that customer behavior alone can be useful for predicting customer value and supporting business decision-making.





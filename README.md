# Chocolate Sales Analysis: Identifying Key Drivers of Sales

## Project Overview
This project focused on analyzing chocolate sales data to uncover the primary factors influencing sales performance. Using Python libraries such as **pandas**, **NumPy**, **matplot-lib**, **scikit-learn**, and **statsmodels**, I performed extensive data cleaning, exploratory data analysis (EDA), feature engineering, and regression modeling. The main objective was to determine whether factors like **price**, **product type**, **seasonality**, or **salesperson performance** had the greatest impact on the number of chocolate boxes sold.

## Key Steps
- **Data Preparation:** Handled missing values, standardized numerical features, formatted dates, and created new variables such as "price per box."
- **Feature Engineering:** Generated dummy variables for categorical data (Sales Person, Country, Product) while focusing the model on the top five salespeople to improve interpretability.
- **Exploratory Data Analysis:** Identified trends in sales volume across products, months, regions, and salespeople.
- **Model Development:** Built an **Ordinary Least Squares (OLS) regression model** to predict log-transformed box shipment quantities, minimizing the influence of outliers.
- **Model Evaluation:** Assessed model performance using **R²** and **Root Mean Squared Error (RMSE)** metrics.

## Key Findings
Based on results of the linear regression I conducted, order behavior (the price per box and the amount of each chocolate sold) is the most influential factor in chocolate sales. Salesperson, country or the type of chocolate being sold had little effect.

Based on the visualizations I created, the month and country in which the sale was made also appeared to be somewhat influential.

## Skills Practiced
- Business analytics and product performance evaluation
- Predictive modeling using regression
- Feature engineering and data transformation
- Statistical analysis and model interpretation

# Walmart Sales: Analysis and Forecasting

## Project Overview

This project leverages historical sales data from 45 Walmart stores located across various regions. Each store houses multiple departments, and the goal is to predict department-level weekly sales for each store. Accurate forecasting enables Walmart to optimize inventory, staffing, and promotional markdowns, particularly during major holidays like the Super Bowl, Labor Day, Thanksgiving, and Christmas. These markdowns often precede high-demand holiday weeks, adding complexity to the forecasting task.


## Dataset Overview

The dataset is sourced from [Walmart Store Sales Forecasting on Kaggle](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/data) and spans from February 5, 2010, to November 1, 2012. It consists of four files

1. stores.csv: 

    - Contains anonymized information about the store type and size.
    - Row Count: 45 / File Size: 1 KB

2. features.csv: 

    - Provides supplementary data, including markdown events, temperature, fuel prices, and more.
    - Row Count: 8,191 / File Size: 579 KB

3. train.csv: 

    - Historical sales data for model training, with weekly sales values included
    - Row Count: 42,2000 / File Size: 12542 KB

4. test.csv: 

    - Identical to train.csv, except weekly sales data is withheld.
    - Row Count: 115,000 / File Size: 2538 KB

## Features

The dataset includes the following key features:

- Store: Identifier for each store.

- Type: Store type, categorized into:
    - Type A: Large stores (supercenters) offering diverse products. Typically located in urban areas.
    - Type B: Medium-sized stores with fewer products, typically in suburban regions.
    - Type C: Small stores with limited product ranges, Often located in rural areas. 

- Size: Store Size in square feet.

- Date: Week of sales (YYYY-MM-DD).

- Temperature: Average weekly temperature.

- Fuel_Price: Weekly fuel cost.

- MarkDown1 - MarkDown5: Promotional markdowns preceding holidays.

- CPI: Consumer Price Index.

- Unemployment: Weekly unemployment Rate.

- IsHoliday: Binary indicator of whether a week is a holiday.

- Dept: Identifier for each department.


## Target Variable

- Weekly_Sales: The weekly sales figure for each store and department, which serves as the target variable for forecasting models.

## Business Problem

How can Walmart optimize staffing, inventory, and promotional strategies at the store-department level by forecasting weekly sales, while accounting for seasonality and holiday impacts?

#### Business Value:

Accurate weekly sales forecasts can:
1.	Optimize Inventory:
    - Predicting weekly sales at the store and department level ensures optimal stock levels, minimizing overstocking or understocking.
2.	Improve Staffing Efficiency:
    - Sales forecasts help schedule staff more effectively, particularly during holiday peaks or promotional periods.
3.	Enhance Promotional Planning:
    - Understanding seasonal trends and holiday spikes allows Walmart to design targeted promotions and markdown strategies.
4.	Reduce Costs:
    - By aligning resource allocation with predicted sales, operational costs are reduced, and profitability improves.



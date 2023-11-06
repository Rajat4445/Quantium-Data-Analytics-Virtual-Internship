# Task 1: Data preparation and customer analytics

## Overview
We need to present a strategic recommendation to Julia that is supported by data which she can then use for the upcoming category
review. However, to do so, we need to analyse the data to understand the current purchasing trends and behaviours. The client is particularly interested in customer segments and their chip purchasing behaviour. Consider what metrics would help describe the customers’ purchasing behaviour.

We have been given dataset on Transaction Data and Purchase Behaviour Data in files named, `QVI_transaction_data.csv` and `QVI_customer_behaviour.csv` respectively.

Also, our end goal is to form a strategy based on the findings to provide a clear recommendation to Julia the Category Manager so make sure your insights can have a commercial application.

## Approach

### Data Preparation
- Performed data exploration of both csv files and checked for null values or duplicate values. After checking for these and correcting any problems, we merged both the files into one single dataframe.
- Dropped unncessary columns, removed any outlier, extracted datatime features from the `Date` column and renamed the columns.
- Extracted features like `Brand name`, `Packet size`, `Flavour description` and `Product Type` from the `Product Name` column.

### Data Exploration & EDA

- 🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥EDIT THIS🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥🔥

<div style="text-align:center; background-color:#add8e6; padding:10px; border-radius:5px;">
    <h2 style="color:#000;">Sales Analysis and Marketing Insights</h2>
</div>

## Sales Drivers

- The primary drivers of sales in the market are the `Budget - older families`, `Mainstream - young singles/couples` and `Mainstream - retirees` shoppers.

## High Spending Segments

- The higher spending on chips within the market is primarily due to the larger population sizes of `Mainstream - young singles/couples` and `Mainstream - retirees` segments. These segments have more buyers.

## Higher Price per Packet

- `Mainstream - midage` and `young singles and couples` segments exhibit a tendency to pay more per packet of chips, which suggests a strong inclination towards impulse buying behavior.

## Impulse Buying Indication

- The higher price per packet observed in the `Mainstream - midage` and `young singles and couples` segments provides a clear indication of impulse buying behavior among these consumer groups.

## Tyrrells Preference

- `Mainstream - young singles and couples` stand out as they are `23%` more likely to purchase `Tyrrells` chips compared to the rest of the population.

## 🔥 Marketing Strategy Suggestion 🔥

- To enhance the category's performance, it is suggested that the Category Manager consider strategically placing `Tyrrells` and smaller packs of chips in discretionary spaces near segments where young singles and couples frequent more often. This approach can increase visibility and encourage impulse buying behavior.


This summary highlights the key insights derived from the sales analysis, providing valuable information for the Category Manager to optimize marketing strategies and boost sales in the market.





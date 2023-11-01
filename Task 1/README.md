# Task 1: Data preparation and customer analytics

## Overview
We need to present a strategic recommendation to Julia that is supported by data which she can then use for the upcoming category
review. However, to do so, we need to analyse the data to understand the current purchasing trends and behaviours. The client is particularly interested in customer segments and their chip purchasing behaviour. Consider what metrics would help describe the customers’ purchasing behaviour.

We have been given dataset on Transaction Data and Purchase Behaviour Data in files named, `QVI_transaction_data.csv` and `QVI_customer_behaviour.csv` respectively.

Also, our end goal is to form a strategy based on the findings to provide a clear recommendation to Julia the Category Manager so make sure your insights can have a commercial application.

## Approach

- Performed data exploration of both csv files and checked for null values or duplicate values. After checking for these and correcting any problems, we merged both the files into one single dataframe.
- Dropped unncessary columns, extracted datatime features from the `Date` column and renamed the columns.
- Extracted features like `Brand name`, `Packet size`, `Flavour description` and `Product Type` from the `Product Name` column.





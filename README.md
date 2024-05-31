# Finance & Fraud Analysis

## Project Overview:

### Goal
The goal of this project is to perform an analysis on credit  
card data to determine the kind of transactions that are most 
likely to be flagged as fraudulent. Including columns that may 
or may not impact that likelihood. The following section has 
the specific questions we have posed to explore the dataset.

### Questions:
* Is there a correlation between distance from home and the last transaction?
    * Is there a difference in fraud rates for transactions occurring at different distances from the home or previous transaction?
* What is the impact of repeat retailer transactions on fraud likelihood?
    * Do first-time transactions at a new retailer have higher fraud rates compared to repeat transactions at previous retailers?
* How does the ratio to median purchase price affect the probability of a fraudulent transaction?
    * Are higher ratios to median purchase prices more indicative of fraud activity vs lower ratios?
* Distance Ratio vs Purchase Methods (Chip, Pin, repeat retail, online)?

### Dataset

For our group project we have decided to perform an analysis on [Credit Card Fraud](https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud). The provided
dataset has the following columns that will help us determine the answers to the above questions: 
* distance_from_home - the distance from home where the transaction happened.
* distance_from_last_transaction - the distance from last transaction happened.
* ratio_to_median_purchase_price - Ratio of purchased price transaction to median purchase price.
* repeat_retailer - Is the transaction happened from same retailer.
* used_chip - Is the transaction through chip (credit card).
* used_pin_number - Is the transaction happened by using PIN number.
* online_order - Is the transaction an online order.
* fraud - Is the transaction fraudulent?

## Approach:

## Credit


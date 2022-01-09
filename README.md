# onlineretailer_market_basket_analysis
This project identifies the most profitable customer groups to target with promotions and create and analyze product groups (market baskets) to anticipate what other products customers would buy for effective promotion campaigns.

Other Contributors: Abdullah Khan, Rohan Garg, Junsu Kim

## Data
- a list of purchases made by about 4000 customers over one year (Dec. 2010 -- Dec. 2011)
- consists of 541,910 rows and 8 columns

## Objectives
1. identify customer purchasing patterns by country
2. create customer segments to identify the most profitable customer groups to target with promotions
3. create and analyze product groups (market baskets) to anticipate what other products customers would buy for effective promotion campaigns

## Data Preprocessing 
- removing any null values/rows, duplicate rows, and rows with negative sales values

## Seasonal and Geographical Analysis 
- the quarterly sales varied greatly between the first and last quarters
- sales figures are highest in UK 

## Product segmentation / clustering 
- using k-means clustering with silhouette evaluation using revealed preference data to create six product categories

## Market Basket Analysis
- Created product recommendation system with 81% accuracy using python applying market basket and lift analysis

## Conclusion:
Online Retailer will be able to better anticipate the categories customers are likely to purchase next with our proposed recommendation system

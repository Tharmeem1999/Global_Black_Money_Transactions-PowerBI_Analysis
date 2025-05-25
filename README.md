# Global Black Money Transactions (Jan 1, 2013 - Feb 21, 2014)

## Introduction

Welcome to the Global Black Money Transactions Analysis! This Analysis, built using Power BI Desktop, leverages an extensive dataset of black money transactions sourced from Kaggle. It covers transactions from January 1, 2013, to February 21, 2014, across various countries, providing crucial insights into money laundering patterns. 

## Data Source
The dataset used for this analysis was originally sourced from Kaggle, but it is no longer available on the platform as of [January 2025]. 

To ensure reproducibility, the dataset has been included in this repository. You can find it in the [`data`](./data) folder.

## Visualizations

This Analysis includes the following visualizations:

-  Map Visualization: Displays the countries where transactions occurred, with bubble sizes representing transaction amounts (USD).
-  Donut Chart: Shows the distribution of transactions by risk score, with the count of transactions as values.
-  Clustered Column Chart: Highlights industries associated with transactions, with industries on the X-axis and transaction amounts (USD) on the Y-axis.
-  Pie Chart: Breaks down the transactions by the source of money (legal or illegal).
-  Stacked Column Chart: Shows transaction types on the X-axis, transaction counts on the Y-axis, and a breakdown by whether they were reported by authorities.
-  Line Chart: Illustrates the trend of transaction amounts over time, with transaction dates on the X-axis and amounts (USD) on the Y-axis.

## Snapshot of the Report 

![img1](https://github.com/user-attachments/assets/0ce35105-299d-4c8b-9b1a-41704747a346)


## Insights

From the Analysis, the following key insights can be drawn:

### [1] Risk Scores Indicating Money Laundering Likelihood

The distribution of transactions by risk scores is as follows:

	Risk Score 1 : 1026 transactions (10.26%)
	Risk Score 2 : 947 transactions  (9.47%)
	Risk Score 3 : 1035 transactions (10.35%)
	Risk Score 4 : 1002 transactions (10.02%)
	Risk Score 5 : 952 transactions  (9.52%)
	Risk Score 6 : 984 transactions  (9.84%)
	Risk Score 7 : 978 transactions  (9.78%)
	Risk Score 8 : 983 transactions  (9.83%)
	Risk Score 9 : 1073 transactions (10.73%)
	Risk Score 10: 1020 transactions (10.20%)
	
Insight: Risk Score 9 accounts for the highest number of transactions.

### [2] Industries Associated with Transactions

The total transaction amounts for different industries are:

	Finance     : $3.74 billion
	Construction: $3.71 billion
	Arms Trade  : $3.60 billion
	Luxury Goods: $3.60 billion
	Real Estate : $3.58 billion
	Casinos     : $3.42 billion
	Oil & Gas   : $3.38 billion

Insight: The finance industry has the highest total transaction amount.
	
### [3] Sources of Money

The origin of money in transactions is broken down as follows:

	Legal  : 2983 transactions (29.83%)
	Illegal: 7017 transactions (70.17%)

Insight: Most transactions (70.17%) originate from illegal sources.

### [4] Transactions Reported to Authorities

For different transaction types, the counts of reported and unreported transactions are:

	Property Purchase: Reported - 432, Unreported - 1654
	Stocks Transfer  : Reported - 384, Unreported - 1599
	Offshore Transfer: Reported - 424, Unreported - 1556
	Cash Withdrawal  : Reported - 368, Unreported - 1610
	Cryptocurrency   : Reported - 397, Unreported - 1576

Insight: Property Purchase is the most frequent transaction type (2086 total), with the majority being unreported.

### [5] Time Series of Transactions

	The highest transaction amounts occurred in May 2013 (Q2), exceeding $450 million, primarily due to stock transfers.



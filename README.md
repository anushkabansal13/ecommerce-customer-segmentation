# ECommerce Customer Segmentation

## Problem
ECommerce businesses send the same messages to all customers without knowing who is loyal, who is about to leave, and who just started buying. This wastes marketing budget and loses customers.

## What We Did
Used **RFM Analysis + K-Means Clustering** to automatically group 4,338 customers into 4 segments based on their actual shopping behavior.

## Dataset
UCI Online Retail Dataset — 541,909 transactions from a UK-based store (2010–2011)

## How It Works

| Step | What |
|---|---|
| Clean Data | Removed nulls, cancellations, bad entries |
| RFM Features | Recency · Frequency · Monetary value per customer |
| Normalize | Log transform + Min-Max scaling |
| Cluster | K-Means (k=4) to group customers |
| Recommend | Business action for each segment |

## Results

| Segment | Customers | Avg Spend |
|---|---|---|
| 🏆 Champions | 10% | £3,899 |
| ❤️ Loyal | 21% | £2,054 |
| 🆕 New / Promising | 25% | £1,757 |
| 😴 Dormant | 44% | £740 |

## Tools
Python · pandas · scikit-learn · matplotlib · seaborn

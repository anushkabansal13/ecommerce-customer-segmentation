# E-Commerce Customer Segmentation

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
| 🏆 Champions | 17.7% | £3,899 |
| ❤️ Loyal | 22% | £2,054 |
| 🆕 New / Promising | 27.1% | £1,757 |
| 😴 Dormant | 33.1% | £740 |

## Tools
Python · pandas · scikit-learn · matplotlib · seaborn

## Dashboard
{<img width="1199" height="1199" alt="CUSTOMER BEHAVIOR   SEGMENTATION" src="https://github.com/user-attachments/assets/81975438-6517-4412-88ce-788df35bc4ee" />
}

## Project Overview

This project focuses on analyzing grocery purchase behavior using Customer Segmentation and Market Basket Analysis techniques.
The objective is to identify different types of customers, understand their buying patterns, and generate product cross-sell recommendations.

By combining K-Means clustering with the Apriori algorithm, the project provides both global and segment-specific insights that support data-driven marketing strategies, personalized recommendations, and inventory planning.

# Technologies Used

Python

Pandas and NumPy

Scikit-learn



## Project Workflow

# 1. Data Loading and Preprocessing

Load the grocery transaction dataset

Convert the date column to datetime format

Handle missing values

Create a unique transaction ID using customer ID and date

# 2. Feature Engineering

Aggregate transaction-level data into customer-level features:

Number of transactions per customer

Total items purchased

Standardize features for clustering

# 3. Customer Segmentation

Apply K-Means clustering to group customers

Label customer segments as:

Frequent Buyers

Regular Buyers

Occasional Buyers

Export customer segmentation results

# 4. Market Basket Analysis (Global)

Create a transaction–item matrix

Apply the Apriori algorithm to identify frequent itemsets

Generate association rules using confidence and lift metrics

Identify commonly purchased product combinations

# 5. Segment-Wise Market Basket Analysis

Merge customer segment information with transaction data

Perform market basket analysis for each customer segment

Identify segment-specific purchasing patterns

# 6. Best-Selling Product Analysis

Identify globally best-selling products

Identify best-selling products for each customer segment

# 7. Cross-Sell Recommendation Generation

Generate global cross-sell recommendations

Generate segment-specific cross-sell recommendations

## Dashboard(Power BI)

<img width="1292" height="723" alt="Screenshot 2025-12-31 141201" src="https://github.com/user-attachments/assets/f8989855-8a50-495b-890d-7a5d5c0aa459" />

<img width="1298" height="716" alt="Screenshot 2025-12-31 141931" src="https://github.com/user-attachments/assets/3e437df8-6042-45ff-9f34-a3ba650fac2a" />

<img width="1283" height="717" alt="Screenshot 2025-12-31 141136" src="https://github.com/user-attachments/assets/9a1f3509-be31-4669-ab4d-3afd08db1338" />

<img width="1304" height="725" alt="Screenshot 2025-12-31 141149" src="https://github.com/user-attachments/assets/d5120c49-6f30-4fc5-9f63-fc64a5d8761d" />

## Key Recommendations

1.Prioritize Frequent Buyers with loyalty programs and personalized offers, as they generate the highest value.

2.Use discounts, bundles, and reminders to convert Occasional Buyers into Regular Buyers.

3.Apply segment-based cross-sell recommendations instead of generic global recommendations for higher relevance and conversion.

4.Use top-selling products such as whole milk and rolls/buns as trigger items for cross-selling.

5.Combine segment bestsellers and segment-level association rules to improve recommendation accuracy.

6.Use global recommendations only as a fallback and rotate suggestions to avoid repetition.




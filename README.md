# Customer Shopping Behavior Analysis

## Project Overview

This is an end-to-end data analysis project focused on understanding customer shopping behavior, revenue trends, product performance, subscription patterns, discount usage, and customer segments.

The project combines Python, SQL, and Power BI to clean, analyze, visualize, and translate customer shopping data into meaningful business insights.

## Tools Used

- Python
- Pandas
- SQL / PostgreSQL
- Power BI
- Jupyter Notebook
- CSV / Excel

## Dataset

The dataset contains 3,900 customer purchase records with 18 columns covering customer demographics, product details, purchase behavior, discount usage, subscription status, and review ratings.

Key fields include:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Season
- Review Rating
- Subscription Status
- Discount Applied
- Shipping Type
- Payment Method
- Frequency of Purchases

## Project Workflow

1. Loaded and explored the raw customer shopping dataset using Python/Pandas
2. Checked data structure, data types, summary statistics, and missing values
3. Handled missing values in the Review Rating column
4. Standardized column names into snake_case for cleaner analysis
5. Created additional features such as age groups and purchase frequency
6. Checked consistency between discount and promo code fields
7. Loaded the cleaned dataset into PostgreSQL for SQL-based analysis
8. Answered business questions using SQL queries
9. Built an interactive Power BI dashboard to present the results visually
10. Developed business recommendations based on the analysis

## Key Business Questions Answered

- Which gender generated the highest total revenue?
- Which customers used discounts but still spent above the average purchase amount?
- Which products had the highest average review ratings?
- How does purchase amount differ between shipping types?
- How do subscribers and non-subscribers compare in customer count, average spend, and total revenue?
- Which products are most dependent on discounts?
- How are customers segmented based on previous purchases?
- What are the top 3 most purchased products in each category?
- Are repeat buyers more likely to subscribe?
- Which age groups contributed the most revenue?

## Dashboard Preview

![Dashboard Preview](images/dashboard_preview.png)

## Key Insights

- Male customers generated higher total revenue than female customers.
- Non-subscribers contributed more total revenue because they represented a larger customer group.
- Average spending between subscribers and non-subscribers was very similar.
- Clothing was one of the strongest categories by revenue and sales volume.
- Young adults contributed the highest revenue among age groups.
- Products such as hats, sneakers, coats, sweaters, and pants showed high discount dependency.
- Loyal customers made up the largest customer segment.
- Express shipping customers had a slightly higher average purchase amount than standard shipping customers.
- Some highly rated products, such as gloves, sandals, and boots, can be used more effectively in product promotion.

## Business Recommendations

- Improve subscription benefits to increase subscriber conversion.
- Create loyalty campaigns for returning and repeat customers.
- Review discount-heavy products to protect profit margins.
- Promote top-rated and best-selling products in marketing campaigns.
- Focus targeted marketing efforts on high-revenue age groups.
- Use customer segmentation to personalize offers and improve retention.
- Monitor discount usage to balance sales growth with profitability.

## Repository Structure

```text
customer-shopping-behavior-analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Customer_shopping_behaviour_analysis.ipynb
│
├── dashboard/
│   └── customer_behavior_dashboard.pbix
│
├── reports/
│   └── Customer Shopping Behavior Analysis.pdf
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

## Files

| File | Description |
|---|---|
| `data/customer_shopping_behavior.csv` | Customer shopping dataset |
| `notebooks/Customer_shopping_behaviour_analysis.ipynb` | Python/Pandas analysis notebook |
| `dashboard/customer_behavior_dashboard.pbix` | Power BI dashboard file |
| `reports/Customer Shopping Behavior Analysis.pdf` | Final project report |
| `images/dashboard_preview.png` | Dashboard screenshot |

## Skills Demonstrated

This project demonstrates:

- Data cleaning with Python/Pandas
- Exploratory data analysis
- Feature engineering
- SQL-based business analysis
- Customer segmentation
- Revenue and product performance analysis
- Power BI dashboard development
- Data storytelling
- Business reporting
- Translating raw data into actionable business recommendations

## Author

**Mohammed Minhajul Islam Saimon**  
Data Analyst | SQL | Python | Power BI | Excel

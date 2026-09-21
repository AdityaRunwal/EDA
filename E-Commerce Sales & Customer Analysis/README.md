# E-Commerce Sales & Customer Analysis

## About the Project
This project is an Exploratory Data Analysis (EDA) of Brazilian e-commerce orders made at the **Olist Store**. The dataset covers 100,000+ orders placed between 2016 and 2018 across multiple marketplaces in Brazil. By unifying multiple related CSV datasets, this analysis provides business insights into sales revenue performance, product category trends, customer purchasing behavior, payment preferences, review ratings, delivery times, and geographic patterns.

## Project Objective
- Analyze sales performance and time-series growth trends over time.
- Identify top-performing product categories by revenue and unit sales volume.
- Evaluate customer retention rates and geographic order distribution across states.
- Understand preferred payment methods and transaction distributions.
- Assess customer review scores and overall customer satisfaction.
- Analyze delivery duration and logistical fulfillment accuracy.

## Dataset
The project utilizes the **Olist Brazilian E-Commerce Public Dataset** available on Kaggle.

## 📊 Dataset

This project uses the **Olist Brazilian E-Commerce Public Dataset**.

The dataset contains information about:

* Customers
* Orders
* Order Items
* Products
* Sellers
* Payments
* Reviews
* Geolocation
* Product Categories

### Dataset Source

The dataset was obtained from Kaggle:

**Olist Brazilian E-Commerce Public Dataset**

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce


## Datasets Used
- `olist_orders_dataset.csv`: Main order timeline and status details.
- `olist_customers_dataset.csv`: Customer locations (cities and states).
- `olist_order_items_dataset.csv`: Product item prices, freight values, and seller links.
- `olist_products_dataset.csv`: Product categories, dimensions, and weights.
- `olist_sellers_dataset.csv`: Seller locations across Brazil.
- `olist_order_payments_dataset.csv`: Payment types, values, and installment counts.
- `olist_order_reviews_dataset.csv`: Customer review scores and feedback text.
- `product_category_name_translation.csv`: English translations for product categories.

## Key Analysis
The analysis is structured into 14 comprehensive sections inside the Jupyter Notebook:
1. Project Introduction
2. Import Libraries
3. Dataset Understanding
4. Data Cleaning
5. Data Integration
6. Feature Engineering
7. Sales Analysis (Monthly revenue and order volume trends)
8. Product Analysis (Top categories by revenue & unit volume)
9. Customer Analysis (Repeat vs one-time customers & state breakdown)
10. Payment Analysis (Payment method distribution)
11. Review Analysis (Review score distribution)
12. Delivery Analysis (Delivery time distribution & delay analysis)
13. Geographic Analysis (Statewise customer distribution)
14. Final Insights

## Technologies Used
- **Python 3**
- **Pandas**: Data loading, cleaning, manipulation, and merging
- **Matplotlib**: Clean and custom data visualizations
- **Seaborn**: Statistical graphics and plot formatting

## Project Structure
```text
E-Commerce Sales & Customer Analysis/
│
├── data/
│   ├── raw/                  # Original Olist CSV files
│   └── processed/            # Cleaned merged dataset (ecommerce_sales_analysis.csv)
│
├── E-Commerce Sales & Customer Analysis.ipynb
└── README.md
```

## Key Insights
- **Sales Growth & Black Friday Peak**: Sales revenue grew steadily throughout 2017, reaching a sharp record peak in November 2017 ($1M+ revenue) driven by Black Friday.
- **Top Product Categories**: `health_beauty`, `watches_gifts`, and `bed_bath_table` generated the highest sales revenue, while `bed_bath_table` led in overall unit volume sold.
- **Customer Retention Opportunity**: Over 97% of customers are one-time buyers, highlighting repeat customer retention as a major strategic opportunity.
- **Credit Card Popularity**: Credit card is the primary payment method for over 70% of transactions, followed by Boleto (bank slip).
- **High Review Ratings**: Over 57% of reviews are 5-star ratings, demonstrating strong overall customer satisfaction.
- **Reliable Fulfillment**: The median delivery time is 10 days, and over 90% of orders were delivered on or before the estimated delivery date.
- **Geographic Concentration**: Customer demand is concentrated in Southeastern Brazil, with São Paulo (SP) accounting for over 40% of total platform orders.

## Author

Aditya Runwal

AI/ML Enthusiast

# 🛒 E-Commerce Sales & Customer Analysis

## 📌 About the Project

This project is an **Exploratory Data Analysis (EDA)** of the **Olist Brazilian E-Commerce Public Dataset**.

The dataset contains information about **100,000+ e-commerce orders** placed between 2016 and 2018. Multiple related datasets are combined to understand sales performance, customer behavior, product trends, payment preferences, reviews, delivery performance, and geographic distribution.

The main focus of this project is:

**Clean → Connect → Analyze → Visualize → Find Insights**

---

## 🎯 Project Objective

The objective of this project is to explore the Brazilian e-commerce data and identify meaningful patterns and business insights.

The analysis focuses on:

* 📈 Sales performance and monthly trends
* 🛍️ Top-performing product categories
* 👥 Customer purchasing behavior
* 💳 Payment method preferences
* ⭐ Customer review ratings
* 🚚 Delivery time and delivery delays
* 🌎 Geographic distribution of customers and orders

---

## 📊 Dataset

This project uses the **Olist Brazilian E-Commerce Public Dataset** from Kaggle.

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

**Olist Brazilian E-Commerce Public Dataset**

[Kaggle Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?utm_source=chatgpt.com)

---

## 📁 Datasets Used

| Dataset                                 | Description                                                          |
| --------------------------------------- | -------------------------------------------------------------------- |
| `olist_orders_dataset.csv`              | Order status, purchase dates, delivery dates, and estimated delivery |
| `olist_customers_dataset.csv`           | Customer IDs and geographic information                              |
| `olist_order_items_dataset.csv`         | Product prices, freight values, and seller information               |
| `olist_products_dataset.csv`            | Product categories and product characteristics                       |
| `olist_sellers_dataset.csv`             | Seller locations and information                                     |
| `olist_order_payments_dataset.csv`      | Payment methods, values, and installments                            |
| `olist_order_reviews_dataset.csv`       | Customer review scores and feedback                                  |
| `product_category_name_translation.csv` | Portuguese-to-English product category translation                   |

---

## 🔗 Data Integration

The project combines multiple related datasets using common identifiers such as:

```text
Customers
    ↓ customer_id
Orders
    ↓ order_id
Order Items
    ↓ product_id
Products
```

Additional information is connected through:

```text
Orders → Payments
Orders → Reviews
Order Items → Sellers
Products → Category Translation
```

This creates a combined dataset that allows different aspects of the e-commerce platform to be analyzed together.

---

## 🧹 Data Cleaning & Preparation

The project includes:

* Handling missing values
* Converting date columns into datetime format
* Checking duplicate records
* Cleaning categorical data
* Handling missing product information
* Translating product categories into English
* Combining multiple datasets using joins
* Creating useful analytical features

---

## ⚙️ Feature Engineering

Additional features were created to support the analysis, including:

* Total order value
* Order year
* Order month
* Year-month
* Delivery time in days
* Delivery delay
* Order day of the week
* Customer order count
* Product sales count

These features help identify patterns that are not directly available in the original datasets.

---

## 📈 Key Analysis

The Jupyter Notebook is organized into the following sections:

1. Project Introduction
2. Import Libraries
3. Dataset Understanding
4. Data Cleaning
5. Data Integration
6. Feature Engineering
7. Sales Analysis
8. Product Analysis
9. Customer Analysis
10. Payment Analysis
11. Review Analysis
12. Delivery Analysis
13. Geographic Analysis
14. Final Insights

---

## 📊 Analysis Areas

### 💰 Sales Analysis

* Monthly sales trends
* Order volume
* Average order value
* Sales performance over time

### 🛍️ Product Analysis

* Top product categories
* Category-wise sales
* Product sales performance

### 👥 Customer Analysis

* One-time vs repeat customers
* Customer distribution by state
* Purchasing behavior

### 💳 Payment Analysis

* Payment method distribution
* Payment values
* Installment patterns

### ⭐ Review Analysis

* Review score distribution
* Customer satisfaction patterns

### 🚚 Delivery Analysis

* Delivery duration
* Delivery delays
* Estimated vs actual delivery performance

### 🌎 Geographic Analysis

* Customer distribution by state
* Geographic concentration of orders

---

## 💡 Key Insights

Some of the major insights identified during the analysis include:

* 📈 **Sales Growth:** Sales showed strong growth during the analyzed period, with a notable increase in November 2017.
* 🛍️ **Top Categories:** Categories such as `health_beauty`, `watches_gifts`, and `bed_bath_table` generated high sales revenue.
* 👥 **Customer Behavior:** The majority of customers placed only one order, showing an opportunity to study repeat purchasing behavior.
* 💳 **Payment Preference:** Credit cards were the most frequently used payment method.
* ⭐ **Customer Reviews:** 5-star reviews represented a large portion of the overall review scores.
* 🚚 **Delivery Performance:** Delivery time and estimated delivery dates were analyzed to understand fulfillment performance.
* 🌎 **Geographic Concentration:** A significant portion of orders came from states in Southeastern Brazil, particularly São Paulo.

---

## 🛠️ Technologies Used

* **Python 3**
* **Pandas** — Data loading, cleaning, transformation, and analysis
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization and plot formatting
* **Jupyter Notebook** — Analysis and documentation

---

## 📂 Project Structure

```text
E-Commerce Sales & Customer Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── E-Commerce Sales & Customer Analysis.ipynb
├── README.md
└── .gitignore
```

> The dataset files are kept locally and are excluded from the GitHub repository using `.gitignore`.

---

## 🚀 What I Learned

Through this project, I practiced:

* Working with multiple related datasets
* Data cleaning using Pandas
* Handling missing values
* Merging datasets using common keys
* Feature engineering
* Exploratory data analysis
* Data visualization
* Extracting meaningful insights from real-world data
* Organizing an end-to-end EDA project

---

## 👨‍💻 Author

**Aditya Runwal**

AI/ML Enthusiast
Exploring **Machine Learning, Deep Learning, and Generative AI**

---

⭐ **If you find this project useful, feel free to explore the notebook and analysis.**

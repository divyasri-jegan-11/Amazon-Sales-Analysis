# 📊 Amazon Sales Performance Analysis

### End-to-End Exploratory Data Analysis & Business Intelligence Dashboard

An end-to-end data analytics project that analyzes Amazon product sales data to evaluate product performance, customer engagement, pricing strategies, and discount trends. The project combines **Python**, **Power BI**, and **Tableau** to transform raw data into actionable business insights.

---

## 🎯 Business Problem

E-commerce businesses generate large volumes of product and customer data, making it difficult to identify high-performing categories, optimize pricing strategies, and understand customer behavior.

This project analyzes Amazon sales data to uncover trends in revenue, customer engagement, product ratings, and discount patterns that can support data-driven business decisions.

---

## 🎯 Project Objectives

* Analyze sales performance across product categories.
* Evaluate customer engagement using ratings and review counts.
* Assess customer satisfaction across categories and subcategories.
* Analyze pricing and discount strategies.
* Develop interactive dashboards for business reporting.
* Build a predictive model to estimate discounted prices.

---

## 📊 Dashboard Preview

> **Power BI Dashboard**

*(https://github.com/user-attachments/assets/b986bdaa-5c30-41de-8079-6ac61c8f13cd)*

---

## 📂 Dataset Overview

The dataset contains Amazon product information, including:

* Product Categories & Subcategories
* Actual Price
* Discounted Price
* Discount Percentage
* Customer Ratings
* Rating Count
* Customer Reviews

The data was cleaned, transformed, and analyzed using Python before building interactive dashboards.

---

## 📈 Key Metrics

| Metric                      | Observation                                          |
| --------------------------- | ---------------------------------------------------- |
| Highest Revenue Categories  | Electronics, Home & Kitchen                          |
| Highest Customer Engagement | Electronics, Home & Kitchen, Computers & Accessories |
| Average Product Rating      | 4.0 – 4.5 ⭐                                          |
| Common Discount Range       | 40% – 70%                                            |
| Best Rated Category         | Office Products                                      |

---

## 🔍 Key Insights

### Revenue Performance

* Electronics and Home & Kitchen generated the highest revenue.
* Revenue was concentrated within a small number of high-performing product categories.
* Computers & Accessories also contributed significantly to overall sales performance.

### Customer Engagement

* Electronics, Home & Kitchen, and Computers & Accessories recorded the highest customer engagement.
* These categories accounted for the majority of product listings and customer reviews.
* Most reviews were submitted by anonymous users.

### Customer Satisfaction

* Most products maintained ratings between **4.0 and 4.5 stars**, indicating strong overall customer satisfaction.
* Office Products and Toys & Games achieved the highest average ratings.
* Tablets recorded the highest-rated subcategory.

### Pricing & Discount Analysis

* Most products were discounted between **40% and 70%**.
* Electronics and Computers & Accessories offered the highest average discounts.
* Wearables and Headphones received the largest promotional discounts among subcategories.

### Predictive Analysis

A Linear Regression model was developed to estimate discounted prices based on actual prices.

**Model Equation**

```
Discounted Price = 0.613 × Actual Price − 2.8
```

Model evaluation indicated a strong linear relationship between actual and discounted prices, while assumption testing suggested opportunities for improving predictive performance by incorporating additional variables.

---

## 💡 Business Recommendations

* Prioritize inventory and promotional campaigns for high-performing categories.
* Optimize discount strategies to improve profitability while maintaining customer demand.
* Encourage verified customer reviews to strengthen customer trust and engagement.
* Explore additional pricing factors to improve predictive pricing models.

---

## 🛠️ Technology Stack

| Category                | Technologies              |
| ----------------------- | ------------------------- |
| Programming             | Python                    |
| Libraries               | Pandas, NumPy, Matplotlib |
| Visualization           | Power BI, Tableau         |
| Development Environment | Jupyter Notebook          |
| Version Control         | Git, GitHub               |

---

## 📁 Repository Structure

```text
Amazon-Sales-Analysis/
│
├── data/
├── notebooks/
├── dashboard/
├── images/
├── README.md
└── LICENSE
```

---

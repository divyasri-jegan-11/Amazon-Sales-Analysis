# 📊 Amazon Sales Data Analysis

## Project Overview
This project analyzes Amazon sales data to identify trends in revenue, customer engagement, and discount patterns. The goal is to understand which product categories perform best and present the insights through interactive dashboards.

## Key Features
- Exploratory Data Analysis (EDA) using Python
- Cleaned and transformed sales data
- Interactive dashboards in Tableau and Power BI


### Power BI Dashboard
![Power BI Dashboard]

![Dashboard](https://github.com/user-attachments/assets/b986bdaa-5c30-41de-8079-6ac61c8f13cd)

## 📂 Project Structure
Amazon-Sales-Analysis

├── README.md  
├── amazon_sales_data.csv  
├── amazon_clean.csv         
├── Amazon.ipynb                 
├── Dashboard.png    
└── LICENSE   


## Installation & Usage
1. Clone this repository:
   ```bash
      git clone https://github.com/divyasri-jegan-11/Amazon-Sales-Analysis.git
   ```
   
2. Install the required Python packages:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the Jupyter notebook or explore the dashboards.

📊 Key Insights
1. Revenue Analysis
 - The Electronics and Home & Kitchen categories generate the most revenue.
 - Top Revenue Subcategories:
      - Computers & Accessories: Laptops, Tablets
      - Electronics: Home Theater, TV & Video, Mobiles & Accessories
      - Home & Kitchen: Heating, Cooling & Air Quality, Kitchen & Home Appliances
  - Price Range: Most products are priced between $10 and $20

2. Customer Engagement
  - The Electronics, Home & Kitchen, and Computers & Accessories categories have the highest customer engagement.
   - These categories account for 97% of the product variety and have the most customer reviews.
   - Electronics and Computers & Accessories also have the second and third highest rating counts.
   - Most customer reviews are submitted by anonymous users.

3. Customer Satisfaction
   - Overall Satisfaction: Most products are rated between 4 to 4.5 stars, reflecting high customer satisfaction.
   - Categories with the Highest Customer Satisfaction:
   - Office Products and Toys & Games.
   - Tablets have the highest average rating among subcategories.
   - No category or subcategory has an average rating below 3.8 stars.

4. Discount Analysis
    - Most discounts fall between 40% and 70%.
    - Categories with the Highest Discounts:
    - Computers & Accessories and Electronics offer the highest average discount percentage.
    - Subcategories with the Highest Discounts:
    - Wearable Technology and Headphones, Earbuds & Accessories.
      
5. Price Prediction Model
     - A linear regression model was created to predict the discounted price from the actual price:
     - Discounted Price = 0.613 × Actual Price – 2.8
       Model Assumptions:
          - The model passed 2 out of 4 assumptions.
          - Heteroscedasticity and normality assumptions were violated, indicating:
               - Other variables may influence the discounted price.
               - Violation of the normality assumption may affect confidence intervals and statistical tests.
                 

## 📌 Conclusion
- Electronics and Home & Kitchen dominate both revenue and customer engagement, indicating these are key product categories for Amazon.
- Customer satisfaction is generally high, with most products receiving positive reviews.
- Discount patterns are consistent, with a majority of discounts ranging between 40% and 70%, making these categories highly attractive to customers.
- Although the linear regression model provides a good approximation for predicting discounted prices, further refinement is needed to meet all assumptions for accurate statistical inference.


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.




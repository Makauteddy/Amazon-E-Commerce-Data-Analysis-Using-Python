# Amazon-E-Commerce-Data-Analysis-Using-Python
## 1. Introduction

E-commerce platforms generate vast amounts of transactional, customer, product, and operational data every day. Analyzing this data enables organizations to understand customer behavior, optimize operations, improve customer satisfaction, and increase profitability.

This project applies Python-based data analytics techniques to an Amazon E-Commerce dataset to uncover actionable insights related to sales performance, customer behavior, product performance, seller effectiveness, inventory management, and operational efficiency. The analysis aims to support data-driven decision-making and demonstrate practical business intelligence and analytical skills.

## 2. Project Description

This project involves the end-to-end analysis of an Amazon E-Commerce dataset containing product transactions, customer interactions, seller information, inventory levels, ratings, reviews, discounts, returns, and delivery performance data.

The analysis was conducted using Python for data cleaning, exploratory data analysis (EDA), statistical analysis, predictive modeling, and data visualization. Business-focused questions were addressed to identify key performance drivers, operational bottlenecks, customer satisfaction factors, and opportunities for revenue growth.

The project concludes with strategic recommendations and dashboard-ready insights that can support executive and operational decision-making.

## 3. Business Problem

E-commerce businesses operate in highly competitive environments where profitability depends on understanding customer preferences, optimizing product offerings, managing inventory efficiently, and delivering excellent customer experiences.

Despite generating large volumes of data, organizations often struggle to answer critical questions such as:

Which products and categories generate the most revenue?
What factors influence customer returns?
How do discounts affect sales performance?
Which sellers contribute most to business growth?
How does shipping performance impact customer satisfaction?
Which products are at risk of stockouts?
What operational factors contribute to revenue leakage?

Without data-driven insights, businesses risk losing revenue through poor inventory management, ineffective pricing strategies, customer dissatisfaction, and operational inefficiencies.

## 4. Data Description

The dataset contains transactional, product, seller, and customer-related information from an e-commerce platform.


user_id	Unique customer identifier

product_id	Unique product identifier

category	Main product category

subcategory	Product subcategory

brand	Product brand

price	Original product price

discount	Discount percentage applied

final_price	Product price after discount

rating	Product rating (1–5 scale)

review_count	Number of customer reviews

stock	Available inventory units

seller_id	Unique seller identifier

seller_rating	Seller performance rating

purchase_date	Transaction date

shipping_time_days	Delivery time in days

location	Customer location/city

device	Device used for purchase

payment_method	Payment method used

is_returned	Return status

delivery_status	Delivery outcome

Derived Variables

## 4. Objectives and Research Questions
Project Objectives

The primary objective of this project is to analyze Amazon E-Commerce data and generate actionable business insights that support revenue growth, customer satisfaction, operational efficiency, and profitability.
## 5. Findings
1. Total revenue generated was $3.05 billion, demonstrating strong overall platform performance and significant market demand.
2. The Electronics category generated over $2.01 billion, contributing more than two-thirds of total revenue and significantly outperforming all other categories.
3. Revenue is highly concentrated in Electronics, while Home, Sports, Beauty, and Clothing contribute substantially lower revenue, indicating opportunities for category diversification.
4. Boat, H&M, and HP emerged as the highest revenue-generating brands, although revenue is distributed almost evenly across all major brands, suggesting a highly competitive marketplace.
5. Monthly sales exhibited strong seasonality and volatility, with revenue reaching its lowest point in February and peaking during October and December.
6. Customer satisfaction remains high, with most ratings ranging between 3.3 and 4.3, and the majority of reviews clustered around ratings above 4.0.
7. Delhi, Mumbai, and Bangalore generated the highest revenue, although the minimal differences between cities indicate balanced purchasing behavior across major urban markets.
8. Higher discount levels were associated with lower revenue performance, suggesting that aggressive discounting reduces profitability rather than stimulating meaningful sales growth.
9. Payment preferences were almost evenly distributed among UPI, Credit Card, Debit Card, and Cash on Delivery, indicating the importance of maintaining all payment channels.
10. Products with higher review volumes tended to maintain more stable and consistently positive ratings, highlighting the importance of customer engagement and social proof.
11. The platform recorded an overall return rate of 11.68%, representing a significant source of revenue leakage.
12. Return rates were nearly identical across all product categories, indicating that returns are driven by platform-wide issues rather than category-specific product problems.
13. Delivery performance has a substantial impact on customer behavior, with return rates remaining near 10.6% for deliveries within five days but increasing sharply to 20.94% when delivery takes six days or more.
14. Shipping delays represent a critical operational bottleneck and are one of the strongest drivers of product returns and customer dissatisfaction.
15 Seller ratings showed little to no relationship with return behavior, suggesting that seller quality is not a primary factor influencing returns.
16. Correlation analysis revealed that product price is strongly associated with both final price and customer ratings, indicating that higher-value products tend to receive better customer feedback.
17. Discounts demonstrated a negative relationship with both revenue and ratings, reinforcing the finding that excessive discounting may harm both profitability and customer perception.
18. Revenue leakage is primarily driven by high return rates and delivery delays, with nearly 30% of shipments experiencing delivery issues and 11.68% resulting in returns.
19. Underperforming sellers with lower ratings may contribute to poor customer experiences and should be monitored to maintain service quality.
## 6. Recommendations
1. Reduce delivery times to five days or less by improving logistics and fulfillment operations, as return rates increase significantly when delivery exceeds six days, directly impacting customer satisfaction and profitability.
2. Optimize discount strategies by using targeted promotions instead of blanket discounts, since higher discount levels are associated with lower revenue performance and reduced profitability.
3. Invest more in the Electronics category through increased inventory, marketing, and product expansion, as it is the highest revenue-generating category and the primary driver of business growth.
4. Implement a company-wide return reduction program focused on improving product information, customer expectations, and post-purchase support, as the overall return rate of 11.68% represents a major source of revenue leakage.
5. Strengthen inventory planning and forecasting for high-demand products and peak sales periods to prevent stockouts, maximize sales opportunities, and improve customer experience.
6. Leverage seasonal demand patterns by increasing inventory availability and marketing efforts ahead of peak revenue months, particularly October and December, to capitalize on periods of high customer demand.
7. Encourage customer reviews and engagement through feedback campaigns and review incentives, as products with higher review volumes tend to maintain stronger ratings and greater customer trust.
8. Diversify revenue streams by growing underperforming categories such as Home, Sports, Beauty, and Clothing to reduce dependence on Electronics and create a more balanced and resilient business portfolio.

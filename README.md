# DSA CAPSTONE PROJECT

### Project Title: Amazon Product Rating and Review

### Project Overview
---
The purpose of this project is to analyze product performance based on customer ratings and reviews from an e-commerce dataset (Amazon). This analysis helps identify which products perform best, uncover customer preferences, and reveal how pricing and discount strategies influence product ratings and engagement which my team and I at **RetailTech Insights** leveraged to generate actionable insights for product improvement, marketing strategy, and customer engagement.

### Data Source
---
The Amazon case study dataset is an Excel file primarily sourced from DSA Data Analysis Capstone Project and this is an open source data which can be downloaded freely from an Open source online such as Kaggle or any other data repository site.

### Data Description or Characteristics
---
-Datasets
Raw Dataset (Amazon case study.xlsx) [view](https://cdn.inst-fs-iad-prod.inscloudgate.net/dbf6d933-81b6-4875-87e8-a8ec97f1fe13/Amazon%20case%20study.xlsx?token=eyJhbGciOiJIUzUxMiIsInR5cCI6IkpXVCIsImtpZCI6ImNkbiJ9.eyJyZXNvdXJjZSI6Ii9kYmY2ZDkzMy04MWI2LTQ4NzUtODdlOC1hOGVjOTdmMWZlMTMvQW1hem9uJTIwY2FzZSUyMHN0dWR5Lnhsc3giLCJ0ZW5hbnQiOiJjYW52YXMiLCJ1c2VyX2lkIjoiNzAwMDAxMTY4NTYwMDkiLCJpYXQiOjE3NTI1OTE4ODQsImV4cCI6MTc1MjY3ODI4NH0.sOF03HSFQ8SL2djiO4SZsIcfz_QuJ9JiIUu6Z_QBl5tQpLLS-9fTBj-RWADMxWiC55KFbKuJaNQRxByuC-aKPQ&download=1&content_type=application%2Fvnd.openxmlformats-officedocument.spreadsheetml.sheet).
It contains information scraped from Amazon product pages, including:
1. Product details: name, category, price, discount, and ratings
2. Customer engagement: user reviews, titles, and content
3. Each row represents a unique product, with aggregated reviewer data stored as comma-separated values


### Tools Used
---
- Microsoft Excel [Download Here](https://www.microsoft.com)
1. Data cleaning
2. Data analysis
3. Visualization
- Github for portfolio building

### Data Cleaning and Preparation
---
My team and I performed the following actions in the initial phase of data cleaning and preparation:
- Data loading and Inspection
- Handling Missing Variables: This was handled using Substitute function, Find and Replace.
- Data cleaning and formatting: Ensure all percentages, numbers, currency values, and IDs are formatted consistently.

### Exploratory Data Analysis
---
EDA involved the exploration of the data to answer some questions about the dataset such as:
1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual price vs the discounted price by category?
6. Which products have the highest number of reviews?
7. How many products have a discount of 50% or more?
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?
9. What is the total potential revenue (actual_price × rating_count) by category?
10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)?
11. How does the rating relate to the level of discount?
12. How many products have fewer than 1,000 reviews?
13. Which categories have products with the highest discounts?
14. Identify the top 5 products in terms of rating and number of reviews combined.

### Data Analysis and Visualization
---
-Excel Dashboard (AMAZON PRODUCT RATING AND REVIEW) 







My team and I utilized Excel to develop calculated columns, detailed pivot tables, which provided key insights into the data. Building on those insights, we generated an interactive and visually engaging dashboard to effectively communicate our findings. 

The dashboard consists of:

- **Key Performance Indicators (KPIs)**
1. Number of Products: 1,351
2. Average of Rating: 4.10
3. Average of Discount Percentage: 48%
4. Total Rating Count: 26,742,111
   
- **Slicer**
1. Price Range Bucket
   
- **Key Insights (Charts)**
1. Category by Discount Percentage 
2. Category Based on Number of Products 
3. Category By  Reviews 
4. Products Based on Ratings
5. Category by Actual Price and Discounted Price
6. Products with the Most Reviews
7. Products with 50% and above Discount Percentage 
8. Distribution of Product Ratings
9. Category Based on Potential Revenue
10. Product Distribution by Price Range Bucket
11. Rating by Discount Percentage
12. Products with Less Than 1000 Reviews
13. Categories with Highest Discounts
14. Top 5 Products by Rating and Number of Reviews

### Data Interpretation or Analysis in Details
---
1. **Category by Discount Percentage:** 
The dashboard reveals that the average discount percentage by product category is 48%. Categories like Computers & Accessories, Electronics, and Home & Kitchen receive the highest average discounts with some exceeding 70%. These likely reflect price-sensitive segments or aggressive marketing tactics.
2. **Category Based on Number of Products:**
From the bar chart, categories such as Home & Kitchen, Electronics, and Computers contain the highest product volumes, indicating high saturation and competition.
3. **Category By  Reviews:**
The bar chart shows Home & Kitchen leading in customer review volume, followed by Electronics. This suggests strong user engagement and potentially high customer interest in these categories.
4. **Products Based on Ratings:**
The graph shows products with IDs B0BQRJ3C47, B09ZHCJDP1 and B0BP7XLX48 topping with ratings 5.0. These are products are top performers in quality and customer satisfaction. They’re ideal for feature promotions, upselling, or influencer marketing.
5. **Category by Actual Price and Discounted Price:**
In the line chart comparison, there's a notable gap between average actual and discounted prices across most categories. Categories like Home & Kitchen Appliances and Computer & Accessories show substantial gaps which are high list prices but aggressive discounting.
6. **Products with the Most Reviews:**
The product with the most review is B07KSMBL2H having 853945 rating counts, followed by B014I8SSD0 and B014I8SX4Y with 426973 and 426973 rating counts respectively. These are the strong customer favorites and possibly bestsellers. 
7. **Products with 50% and above Discount Percentage:**
The bar chart shows around 751 products meet this criterion. Most are from highly competitive categories indicating a potential sign of market saturation or price war.
8. **Distribution of Product Ratings:**
The horizontal bar chart reveals a healthy cluster of products rated between 4.0 and 4.4, suggesting generally positive customer feedback. Few fall below 3.5, indicating good product satisfaction overall.
9. **Category Based on Potential Revenue:**
The bar chart shows that Electronics, Computer & Accessories and Home & Kitchen dominates in potential revenue. This suggests where the company can focus its marketing and inventory investment.
10. **Product Distribution by Price Range Bucket:**
The doughnut chart shows that the majority of products fall under the ₹500 price range, with smaller portions within ₹200-₹500 and above ₹200. This ₹500 range dominance indicates a price sweet spot for customers.
11. **Rating by Discount Percentage:**
From the bar chart, there’s a visible decline in product rating as the discount increases. This trend suggests that high discounts may be associated with lower product quality or lower customer satisfaction.
12. **Products with Less Than 1000 Reviews:**
The bar chart confirms that a large number of products fall below the 1,000 review mark, with some having less than 100. These products may be new, poorly marketed, or underperforming in terms of visibility.
13. **Categories with Highest Discounts:**
The chart shows Computer Accessories, Electronics, and Home & Kitchen as top categories for heavy discounting, many with over 70% average discounts.
14. **Top 5 Products by Rating and Number of Reviews:**
From the pie chart, B07KSMBL2H, B014I8SX4Y, B014I8SSD0, B01DEWVZ2C, B07GQD4K6L, B07GPXXNNG are the top products based on amount of reviews with an average rating of 4.25. These products not only have high ratings but also massive review counts which makes them ideal for promotion and brand trust.






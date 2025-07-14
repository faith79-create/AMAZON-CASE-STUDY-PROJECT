# 🛍️Amazon Product Review Analysis (DSA Project)

A detailed Excel-based analytics project on Amazon product reviews, discounts, and pricing. Designed during my time at the DSA Incubator Hub, this project uses pivot tables, slicers, calculated fields, and interactive dashboards to extract actionable insights on product performance, category trends, customer engagement, and revenue.

🔍 Objective: Analyze Amazon product and review data to derive business insights using pivot tables, slicers, calculated columns, and data visualizations.
--------

## Table of Contents

-  [Project Context](#project-context)
-  [Dataset Description](#dataset-description)
-  [Key Analytical Tasks & Solutions](#key-analytical-tasks-solutions)
-  [Key Highlights/Summary](#key-highlights-summary)
-  [About Me](#about-me)
-  [Contact](#contact)
-----------------------

### 🏢 Project Context

Client Name: RetailTech Insights

Industry: E-commerce Analytics

Role: Junior Data Analyst

🔧 Tools Used: Microsoft Excel, Data Cleaning [Download here](https://microsoft.com) 
    Pivot Tables, Charts, & Slicers.
------

### 🧾 Dataset Description

- Total Records: 1,465
- Columns: 16
- Source: Web-scraped Amazon product review data
- Each row represents: A unique product
- Fields included:.
  -  Product name
  -  Category
  -  Actual price & Discounted price
  -  Discount %
  -  Rating
  -  Number of Ratings (Rating Count)
  -  Review content (aggregated in some columns)
  -  Revenue potential fields (derived)
  -------

  ### 📊 Key Analytical Tasks & Solutions
  
 | # | Task Description                                                        |         Excel Tools Used                         |               
 |---|-------------------------------------------------------------------------|--------------------------------------------------|
 | 1 |  What is the average discount % by product category                     | Pivot Table + Average Formula                    |
 | 2 |  How many products are listed under each category?                      |  Pivot Table + Count                             |
 | 3 |  What is the total number of reviews per category?                      |   SUM of Rating Count by category                |
 | 4 |	  Which products have the highest average ratings?	                   |   Sorting based on calculated Average Rating     |
 | 5 |  What is the actual vs discounted price by category?	                   |   Grouped Bar Chart + Pivot Summary              |
 | 6 |	Which products have the highest number of reviews?	                   |  Top-N Analysis using Sorting + Pivot Table      |
 | 7 |	How many products have ≥ 50% discount?	                               |  Filter logic on Discount column                 |
 | 8 |	What is the distribution of product ratings (e.g., 3.0, 4.0, etc.)?	   |   Grouped histogram with Pivot Count             |
 | 9 |	Total potential revenue (actual_price × rating_count) per category?    | 	New Calculated Column + Pivot Table SUM         |
 | 10 |	Unique product count per price range bucket (<200, 200–500, >500)?	   |  IF formulas + Donut Chart                       |
 | 11 |	Relationship between rating and discount level?	                       |   Scatter Line Chart (2 y-axes)                  |
 | 12 |	How many products have fewer than 1,000 reviews?	                     |   COUNTIF Formula + Bar Chart                    |
 | 13 |	Categories with highest average discount?                              |   Sorted Pivot Table by Discount%                |
 | 14 |	Top 5 products by combined review count and rating	                   |  Ranking logic using SUM(Rating × ReviewCount)   |
 -------------

 ### 🧠 Key Highlights/Summary

- High Discount Rating: Many discounted items still received poor ratings. Price cuts alone won’t ensure customer satisfaction.
- Most Reviewed Category: Electronics had the most reviews but also a wide range in satisfaction.
- Revenue Optimization: Focus marketing efforts on mid-priced, highly rated products in "Home Kitchen" and "Accessories".
- Product Opportunity: Products with moderate ratings but high volume reviews may benefit from improved quality or targeted feedback campaigns.
- Fastest Products: A few products drive massive engagement. Promoting these further can help with cross-selling.
-----

  ### 👨‍💻 About Me
 ***Faith Udokanma Ihueze***  
  ##### 🎓 B.SC Accounting, 📊 Data Analyst,
  ##### I’m passionate about simplifying data into impactful
  ##### visuals and helping businesses make better decisions. 
  ##### This project is a reflection of my journey in the DSA Incubator Hub on Excel-based analysis.

### 📫 Contact
- Email: **faithamaefule@yahoo.com**
- Phone: +234 703 083 4411
- Github: [http://github.com/faith79-create]







# Sales-Project
### INTRODUCTION 
This Excel project focuses on analyzing the sales of high-demand fast food items. The dataset includes important details such as each menu item's unique ID, name, category, and pricing information. This analysis aims to generate actionable insights to support strategic decision-making and enhance operational effectiveness. 

**Table of Contents**
- Project Overview
- Project scope
- Project objectives  
- Expected outcome 
- Document purpose  
- Use case 
- Data source 
- Data cleaning and processing  
- Data Analysis 
- Data Visualization  
- Recommendation  
- Conclusion

  
**Project Overview**
  
This project involves analyzing sales data to uncover trends, evaluate performance, and generate actionable insights for business improvement. The analysis focuses on understanding key sales drivers and product performance across periods. 

**Project Scope**

The project covers: 
- Sales data exploration and preparation
- Identification of sales trends and patterns
- Customer segmentation and purchasing behavior
- Product performance analysis
- Time-based (monthly/quarterly/yearly) trend analysis

**Project Objectives**
  
- Analyze overall sales performance across different regions and periods
- Identify best-selling and underperforming products
- Understand customer purchasing patterns
- Provide insights to support marketing and sales strategies

**Expected Outcome**
  
- Clean and structured sales dataset
- Key performance metrics (e.g., total sales, average order value, top customers)
- Visualizations of sales trends, customer segments, and product performance
- Strategic recommendations for business growth
- A professional portfolio project showcasing data analysis and visualization skills

**Document Purpose**
   
This document outlines the steps to analyze a sales dataset, including the data source, data cleaning, analysis techniques, visualization, and business recommendations. It serves as a demonstration of analytical skills and understanding of data-driven decision-making. 

**Use Case**
  
The analysis can be used by: 
- Sales managers to identify areas of high/low performance 
- Marketing teams to target promotions effectively
- Product teams to assess product popularity and returns
- Executives to make strategic decisions using data insights

**Data Source**
  
  - Format: Excel/CSV file
  - Column: Order details ID, Order ID, Order Date, item name, item ID, Category,   	 	and price
  - Source: Maven Analytics
 
**Data Cleaning and Processing**
    
 Steps involved:
 - Handled missing values and duplicates
 - Created new columns such as Hours and Minutes
 - Standardized product names and categories

**Tools used: Excel.**

**Data Analysis**

The primary aim of this analysis is to extract valuable insights regarding high-demand fast food items by thoroughly examining key factors. This multifaceted exploration encompasses several important objectives. First, it seeks to understand the daily customer demand for fast food and identify any peak ordering hours. Second, the analysis aims to highlight any bestselling items. Furthermore, a detailed investigation into this year’s revenue will be conducted to assess seasonal sales trends. 
Additionally, the analysis will explore whether there are specific fast food items that could be removed from the menu and identify any promotional opportunities that could be leveraged. It will also look into which categories may have been previously removed and their overall impact on sales. 
 
The key benefits of this analysis include enhanced operational efficiency, leading to better staff scheduling and inventory management. It will provide valuable customer insights, allowing us to identify slower days and aid in financial planning through improved revenue projections and cost management. Moreover, it will support strategic decision-making, inform marketing campaigns, and optimize the menu. Ultimately, this will enhance the customer experience by improving service quality and engagement strategies.

   **At certain times of the day, with more or fewer order** 
The main goal of this analysis is to identify the specific times of day that experience either a higher or lower volume of fast food orders, using order time as a metric for customer transactions. Understanding these patterns is essential for gaining insights into daily traffic flows, recognizing peak and off-peak periods, and enhancing overall business operations. 
 
To accomplish this, a pivot table has been created, with the time column organized in the rows section and order ID in the values section to calculate the total number of orders placed within each time interval. The findings were then represented visually through a line trend graph, making it easier to analyze the data effectively. 

![](https://github.com/Abdulquadri2025/Sales-Project/blob/main/Certain%20time%20of%20the%20day%20with%20more%20or%20fewer%20order.jpg)

**From the analysis above**

- 12 pm has the highest time of order (1659)
- 1 pm has the second-highest (1558). Continued high activity due to leisure and social activities
- It moved higher a little at 4 pm due to the closing hour
- 10 am and 11 pm have the lowest count (5 and 11), possibly due to early and late hours or different activities

    **Day with the highest Sales**

The main goal of identifying the day with the highest number of orders is to uncover peak customer demand periods. This insight helps the business make informed decisions about: 
- Staff scheduling to ensure sufficient manpower during busy times
- Inventory planning to prevent stock shortages on high-traffic days
- Targeted promotions and marketing on days with the most engagement
- Improving customer experience by reducing wait times and service delays during  
 	peak periods

  ![](https://github.com/Abdulquadri2025/Sales-Project/blob/main/Day%20with%20the%20highest%20sales.jpg)

**From the Analysis above**
   
- Monday stands out with the highest sales (26007), marking it as the first and arguably the most significant day of the week for many workers. Following closely,
- Friday ranks second in sales (23708), which is often associated with social gatherings and celebratory end-of-week treats.
- Both Sunday and Tuesday demonstrate a steady mid-week sales count (23226 and 23356), suggesting stable dinner habits among consumers.
- Saturday experiences a slight dip in sales (21171), which may be attributed to the weekend's varying activities.
- Wednesday records the lowest sales (19902), likely reflecting its positioning as the midpoint of the week.
- This analysis highlights the patterns in consumer behavior throughout the week, offering valuable insights for planning and strategy.

  **How much money was made, and identify any seasonality in sales?**
   
This question aims to evaluate the total annual revenue and identify any sales patterns that may vary over time. By doing so, we can gain valuable insights into the financial performance of the fast food sector and recognize seasonal trends, which will help us understand how sales fluctuate throughout the year. 
We utilized a monthly sales dataset, which we visualized using a line trend graph. For the total revenue analysis, we pivoted the data to calculate the sum of revenue. This visual representation offers a clear overview of sales dynamics over the designated period, effectively highlighting recurring patterns or anomalies that may need further investigation. 
 
**Total Revenue:** $159,218 
**Seasonality in Sales**

  ![](https://github.com/Abdulquadri2025/Sales-Project/blob/main/Month%20with%20the%20highest%20sales.jpg)

**From the Analysis Above**

- March is the highest monthly sales 
- February is the lowest monthly sales

  **How did the Categories contribute to the total revenue?**
    
This analysis focuses on evaluating the revenue generated by various categories of fast food and gauging their impact on the overall financial performance of the offerings. By examining the popularity of different categories among customers, businesses can make informed decisions regarding their menu design, pricing strategies, and marketing efforts. Understanding the contribution of each category to total revenue allows for the optimization of the product mix, ultimately enhancing both profitability and customer satisfaction. To facilitate this understanding, the percentage contribution of each category has been calculated and illustrated 

**Using a pie chart**

   ![](https://github.com/Abdulquadri2025/Sales-Project/blob/main/Top%20and%20Least%20category.jpg)

This analysis above shows that the Category contributed well to the total revenue for the year

**Data Visualization**
    ![](https://github.com/Abdulquadri2025/Sales-Project/blob/main/Data%20Visualization.jpg)

**Recommendations:**

- Focus on High-Performing Items: 
Promote bestsellers like the Hamburger and Korean Beef Bowl through featured combos or meal deals to boost customer interest and up-sell opportunities.
- Expand Popular Cuisine Options: 
Since Asian cuisine leads in popularity, consider expanding the Asian menu with more variety or fusion options to further attract interest. 
- Optimize Menu for Profitability: 
Evaluate cost vs. pricing of top items to ensure they are also high-margin products. Strategically place them on the menu to catch customer attention. 
- Encourage Upsells: 
With an AOV of ~$29.65, suggest add-ons like drinks or desserts at checkout to nudge orders toward the $35–$40 range.

**Conclusion**
 
The sales data analysis provided a clear view of the sales performance across various dimensions. With actionable insights from product, customer, and analysis, the business can make informed strategic decisions. This project demonstrates proficiency in data cleaning, analysis, and visualization tools. 
Thank you for reading 
I am seeking an opportunity within a data analyst group in an organization where I can effectively showcase my skills and take on greater responsibilities. I am eager to continue learning and grow alongside the organization, contributing in meaningful ways that will be advantageous for both my professional development and the success of the team. 
 
You can reach me at aregbeabdulquadri@gmail.com 
 
**THANK YOU** 



 





 

 













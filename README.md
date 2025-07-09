# Overview 📖
Business success isn’t just about attracting new customers; it’s about ensuring that those who have purchased once choose to return. To support this, I developed a **Power BI dashboard** that provides stakeholders with clear insights into **Customer Repeat Value (CRV)** and the key factors influencing it. This metric empowers businesses to fine-tune their strategies, enhance customer loyalty, and ultimately increase both **lifetime customer value** and **overall revenue**.

## Table of Contents 📚
- [Introduction and Situation](#introduction-and-situation)
- [Data Preparation and Visualization Approach](#data-preparation-and-visualization-approach)
- [Business Questions](#business-questions)
- [Insights](#insights)
- [Recommendations](#recommendations)

# Introduction and Situation
This project was initiated in response to a strategic request from the **Director of Customer Engagement**, seeking a deeper, data-driven understanding of repeat customer behavior to support upcoming growth initiatives. While anecdotal evidence indicated that repeat purchases play a significant role in the company’s revenue, there was no systematic analysis available to validate these insights or uncover detailed patterns.

The goal of this project is to analyze **monthly and seasonal trends** in repeat purchases, measure the contribution of repeat customers to overall sales, and evaluate the impact of marketing campaigns on encouraging customer loyalty. By leveraging transaction and campaign data, the analysis aims to provide clear, actionable insights that will help optimize customer engagement strategies, improve campaign effectiveness, and ultimately drive sustainable business growth.

# Data Preparation and Visualization Approach
Dataset used for the project can be accessed [here]((https://github.com/sindhujasankararaman/Repeat-Customer-Rate-Analysis-using-Power-BI/blob/main/repeat_customer_rate_data.cs)).

To ensure the accuracy and quality of the analysis, I utilized Power Query within Power BI for comprehensive data cleaning and transformation. This process involved:

- Removing duplicates and handling missing values  
- Formatting and standardizing date and categorical fields  
- Merging and shaping datasets such as customer transactions, campaign data, and regional information  
- Creating calculated columns and measures to support analysis  

For the visualization and insights delivery, I leveraged Power BI’s rich visualization capabilities to build interactive dashboards that illustrate:

- Monthly and seasonal trends in repeat customer purchases  
- Geographic distribution of repeat customer rates and orders  
- The impact of marketing campaigns on repeat purchase behavior  
- Key metrics like **repeat customer rate**, **sales contribution**, and **purchase frequency**

This combination of Power Query for data preparation and Power BI for visualization enabled a seamless end-to-end analytics workflow, providing clear and actionable insights for stakeholders.

To support deeper exploration, the dashboard is fully interactive—users can hover over visuals and drill down by month, season, or year, enabling customized insights based on temporal trends.

Link to the Dashboard

# Business Questions
I have delved deep into the data to answer the following business questions:

1. What is the total size of our customer base, and how many of them are repeat customers?  
2. What percentage of our customers are repeat buyers, and how does this reflect on our customer loyalty?  
3. How does the repeat customer rate vary across different time periods, such as months and seasons?  
4. Are there regional differences in the repeat customer rate that we should be aware of?  
5. How do repeat customers contribute to overall sales volume and revenue compared to new customers?  
6. What marketing efforts have been most effective in driving repeat purchases within this customer base?

# Insights

- Out of **5,000 customers**, **1,474 returned**, resulting in a **repeat customer rate of 29.5%**.  
- **Summer** had the highest repeat rate (**30.4%**), indicating stronger customer engagement during that season.  
- **Spring** had the lowest repeat rate (**29.1%**), suggesting weaker engagement.  
- **Referral-based marketing campaigns** were highly effective in driving repeat purchases, emphasizing the influence of **peer recommendations**.  
- **Email promotions** showed minimal impact on repeat purchases, indicating potential fatigue or lack of effectiveness.

# Recommendations

- **Replicate and scale summer engagement strategies** across other seasons to boost repeat purchases year-round.  
- **Improve spring campaign efforts** by enhancing the customer experience or offering more compelling promotions during that period.  
- **Invest more in referral-based marketing**, possibly by launching or expanding referral incentive programs.  
- **Re-evaluate the email marketing approach**—consider A/B testing new subject lines, personalization strategies, or better segmentation to increase impact.




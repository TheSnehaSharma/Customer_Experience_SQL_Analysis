# Customer_Experience_SQL_Analysis
## **Project Overview**
This project explores customer behavior and demographic insights through structured data analysis using SQL and Python (pandas, matplotlib). The primary goal is to extract actionable patterns that can improve customer experience, engagement, and retention strategies.
## **Project Objectives**
1. Customer Segmentation and Profiling - To classify customers based on demographics such as age, location, and gender to enable targeted marketing and personalized experiences.
2. Retention Analysis - To analyze customer retention using feedback scores, satisfaction ratings, and products purchased to identify loyalty drivers and reduce churn.
## **Data Description**
The dataset consists of customer experience and transactional records, including demographic details, purchase behavior, and feedback scores. The key metrics are:
1. Customer_ID – Unique ID assigned to each customer
2. Age – Customer's age, ranging from 18 to 70
3. Gender – Gender classification of the customer, either Male or Female.
4. Location – Geographic category indicating whether the customer is from an Urban, Suburban, or Rural area.
5. Number of Interactions – Total number of interactions made by the customer.
6. Feedback Score – Customer's feedback rating on a scale of 1 to 5.
7. Satisfaction Score – Overall satisfaction level rated by the customer on a scale from 1 to 10.
8. Products Purchased – Count of products bought by the customer.
9. Products Viewed – Count of products browsed or viewed by the customer.
10. Time Spent on Site – Total time (in minutes) spent by the customer during their website visit.
## **Executive Summary**
Female customers and the 30-40 age group drive the most purchases but face notable churn, especially in urban areas. Customers with moderate engagement (fewer product views and 10–50 minutes spent) show higher retention and satisfaction. About one-third of customers are churned, with retained and churned groups showing only slight differences in feedback and satisfaction scores, suggesting these metrics alone do not strongly predict retention.
## **Key Insights**
1. Customer Demographics -
   - The dataset comprises 52.4% male and 47.6% female customers.
   - Age distribution includes 22.9% young adults (18–30 years), 38.4% middle-aged adults (31–50 years), and 34.9% older adults (51–70 years).
   - Geographically, customers are distributed as 31.2% rural, 34.4% suburban, and 34.4% urban residents.
2. Retention Analysis -
    - Female customers report higher satisfaction and purchase frequency but have a higher churn rate of 31.5% compared to 29.7% for males.
    - Urban customers churn the most at 35.7%, followed by rural customers at 28.8%, while suburban customers are the most retained at 27.0%.
    - The 30–40 age group has the lowest churn at 24.1%, making them the most retained; the 20–30 group churns the most at 33.9%, followed by older adults.
    - Customers viewing fewer than 10 products have the lowest churn at 26.9%; churn rises with more views, reaching 33.5% for those viewing over 40 products.
    - Time spent on-site between 30-50 minutes correlates with lower churn (27.9%), while durations under 20 or over 50 minutes lead to higher churn (33.4%).
    - Customers with moderate interactions have the highest retention at 28.8% churn; those with very low or very high interactions churn at 33.4% and 30.1%, respectively.

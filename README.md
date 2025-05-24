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
1. **Customer Demographics** -
   
   - The dataset comprises _52.4%_ male and _47.6%_ female customers.
   - Age distribution includes _22.9%_ young adults (18–30 years), _38.4%_ middle-aged adults (31–50 years), and _34.9%_ older adults (51–70 years).
   - Geographically, customers are distributed as _31.2%_ rural, _34.4%_ suburban, and _34.4%_ urban residents.
![Customer Distribution by Age](https://github.com/TheSnehaSharma/Customer_Experience_SQL_Analysis/blob/main/media/age.png)
![Customer Distribution by GEnder and Location](https://github.com/TheSnehaSharma/Customer_Experience_SQL_Analysis/blob/main/media/gender&location.png)
2. **Retention Analysis** -
   
    - Female customers report higher satisfaction and purchase frequency but have a higher churn rate of _31.5%_ compared to _29.7%_ for males.
    - Urban customers churn the most at _35.7%_, followed by rural customers at _28.8%_, while suburban customers are the most retained at _27.0%_.
    - The 30–40 age group has the lowest churn at _24.1%_, making them the most retained; the 20–30 group churns the most at _33.9%_, followed by older adults.
    - Customers viewing fewer than 10 products have the lowest churn at _26.9%_; churn rises with more views, reaching _33.5%_ for those viewing over 40 products.
    - Time spent on-site between 30-50 minutes correlates with lower churn _(27.9%)_, while durations under 20 or over 50 minutes lead to higher churn _(33.4%)_.
    - Customers with moderate interactions have the highest retention at _28.8%_ churn; those with very low or very high interactions churn at _33.4%_ and _30.1%_, respectively.
![Retention vs Different Metrics](https://github.com/TheSnehaSharma/Customer_Experience_SQL_Analysis/blob/main/media/retention_graphs.png)
## **Recommendations**
1. _Targeted Retention Strategies for Female Customers_ - Despite high satisfaction and purchase rates, female customers show elevated churn. Implement personalized retention campaigns specifically aimed at urban female segments where churn is highest.
2. _Focus on Suburban Markets_ - With the highest retention rate (72.9%), suburban customers represent a stable customer base. Invest in maintaining satisfaction through targeted communication, exclusive offers, and consistent service quality.
3. _Engage and Retain Young Adults (18–30)_ - This group shows the highest churn (33.9%). Introduce gamified engagement and early loyalty incentives to boost stickiness among younger users.
4. _Optimize Product Browsing Experience_ - Encourage efficient browsing by streamlining the product discovery journey. Customers viewing fewer than 10 products show lower churn (26.9%), indicating satisfaction and ease of finding desired items.
5. _Encourage Balanced Customer Interactions_ - Users with moderate interactions exhibit the best retention. Implement features (e.g., helpful chatbots, reminder emails) to nudge inactive users without overwhelming them, avoiding both extremes of disengagement and fatigue.
## **Additional Links**
Dataset - [Customer Experience Dataset](https://www.kaggle.com/datasets/ziya07/customer-experience-dataset)
Colab Notebook - [Customer Experience Analysis](https://colab.research.google.com/drive/19YlnkESRq_Q-XI7WQf-cP2HOsftQZXVo?usp=sharing)

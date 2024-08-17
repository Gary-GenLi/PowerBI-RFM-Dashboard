# PowerBI-RFM-Dashboard
## Table of Contents
- [1.Introduction](#1Introduction)
- [2.ETL Workflow](#2ETL-Workflow)
- [3.KPIs](#3KPIs)
- [4.Modeling](#4Modeling)
- [5.Dashboard](#5Results)
- [6.Lesson Learned](#6Lesson-Learned)
## 1.Introduction
The managements of one retail bank want to know Customer loyalty and their sales contribution by segments defined with RFM methodology. The request is to have a robust and long term production solution which can help Busines – CRM Services department to improve profitability and increase customer loyalty through respective Campaign Planning & Design based on result of analysis. 
## 2.ETL Workflow
![image](https://github.com/user-attachments/assets/60f5fffc-0847-48d5-9678-ff19714972e5)
## 3.KPIs
**Metrics Creation:** Devised measures to compute total transaction amounts and overall customer counts.

**RFM Analysis:** 
- Recency: How recently a customer has made a purchase. Scoring: Customers scoring 1 had a recency greater than the 75th percentile; 2 for recency greater than 50th percentile; 3 for greater than 25th, and 4 for the rest. The rationale is that recent transactions indicate a higher likelihood of future engagements.

- Frequency: How often a customer makes a purchase. Scoring: Customers scoring 4 exceed the 75th percentile in frequency; 3 for above 50th percentile; 2 for above 25th, and 1 for the rest. The purchase cycle can influence frequency, and understanding this can drive targeted marketing efforts.

- Monetary Value: How much money a customer spends on purchases. Scoring: Customers scoring 4 surpass the 75th percentile in monetary contributions; 3 for above 50th percentile; 2 for above 25th, and 1 for the rest. The goal is to emphasize high spenders without neglecting consistent, albeit lower-spending, customers.

## 4.Modeling 
![workflow](images/20240805045805.png)
## 5.Dashboard
Visualize the hypothetical data and create the dashboard using PowerBI.
![20240805051627](https://github.com/user-attachments/assets/e7c1b598-5ce3-4487-9c72-40f772c787b2)
## 6.Lesson Learned
RFM (Recency, Frequency, Monetary) analysis in Power BI using DAX is a powerful tool for customer segmentation, enabling businesses to tailor marketing strategies to specific customer groups. By identifying high-value customers, businesses can focus on retention efforts and prevent churn. Targeted marketing campaigns can be designed based on customer behavior, leading to improved engagement and conversion rates. Additionally, RFM analysis aids in resource allocation, product development, and inventory management, ensuring that efforts are directed where they have the most impact. Ultimately, this data-driven approach enhances customer experiences, improves marketing effectiveness, and boosts customer lifetime value (CLV).


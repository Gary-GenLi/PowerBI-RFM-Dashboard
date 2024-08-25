# PowerBI-RFM-Dashboard

## Table of Contents
- [1. Introduction](#1-introduction)
- [2. Workflow Diagram](#2-workflow-diagram)
- [3. KPIs](#3-kpis)
- [4. Modeling](#4-modeling)
- [5. Dashboard](#5-dashboard)
- [6. Lessons Learned](#6-lessons-learned)
  
## 1. Introduction

The management of a retail bank seeks to evaluate customer loyalty and their contribution to sales by segmenting customers using the **RFM (Recency, Frequency, Monetary)** methodology. The goal is to develop a robust, long-term solution that provides actionable insights for the **Business – CRM Services** department, ultimately enhancing profitability and increasing customer loyalty through targeted campaign planning and design.

## 2. Workflow Diagram

![20240824235640](https://github.com/user-attachments/assets/724a63ec-9b7b-4f42-9fb3-1a50915b0676)

## 3. KPIs

**Metrics Creation:** Developed measures to calculate total transaction amounts and overall customer counts, forming the basis for the RFM analysis.

### RFM Analysis: 

- **Recency:** Measures the time elapsed since a customer's last purchase.  
  **Scoring:**  
  - Score **1**: Recency > 75th percentile  
  - Score **2**: Recency > 50th percentile  
  - Score **3**: Recency > 25th percentile  
  - Score **4**: Recency ≤ 25th percentile  
  *Recent transactions are strong indicators of future engagement.*

- **Frequency:** Measures how often a customer makes a purchase.  
  **Scoring:**  
  - Score **4**: Frequency > 75th percentile  
  - Score **3**: Frequency > 50th percentile  
  - Score **2**: Frequency > 25th percentile  
  - Score **1**: Frequency ≤ 25th percentile  
  *Understanding purchase frequency can drive effective targeted marketing efforts.*

- **Monetary Value:** Measures the total amount a customer spends.  
  **Scoring:**  
  - Score **4**: Monetary Value > 75th percentile  
  - Score **3**: Monetary Value > 50th percentile  
  - Score **2**: Monetary Value > 25th percentile  
  - Score **1**: Monetary Value ≤ 25th percentile  
  *High spenders are prioritized, while consistent, lower-spending customers are also recognized.*

![RFM Segments](https://github.com/user-attachments/assets/1a6c2f20-2609-4f44-840c-df18e691cde9)

## 4. Modeling 

Data modeling in Power BI was conducted to ensure accurate and efficient analysis of customer data, facilitating the generation of meaningful insights.

![Data Modeling Workflow](images/20240805045805.png)

## 5. Dashboard

The dashboard was created in Power BI, visualizing segmented customer data. This tool allows stakeholders to interpret the analysis easily and make data-driven decisions. *(Note: All data displayed is simulated.)*

![Dashboard Example](https://github.com/user-attachments/assets/e7c1b598-5ce3-4487-9c72-40f772c787b2)

## 6. Lessons Learned

Conducting **RFM analysis** using **DAX in Power BI** has proven to be an effective approach for customer segmentation. This method allows businesses to tailor their marketing strategies to specific customer segments, focusing on high-value customers to enhance retention and prevent churn. Targeted campaigns based on customer behavior can significantly improve engagement and conversion rates.

Moreover, RFM analysis provides valuable insights for resource allocation, product development, and inventory management, ensuring that efforts are concentrated where they are most effective. Ultimately, this data-driven strategy improves customer experience, enhances marketing efficiency, and increases **Customer Lifetime Value (CLV)**.

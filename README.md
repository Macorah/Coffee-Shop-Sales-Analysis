# Coffee Shop Sales Analysis ☕📊
This project involved cleaning, analyzing, and visualizing transaction data for a frictional coffe shop using **SOL**, **Excel**, and **Power BI**

---
[Project Overview](#project_overview)

[Data Source](#data_source)

[Tools Used](#tools_used)

[Key Buisness Questions](#key_buisness_questions)

[Data Cleaning](#data_cleaning)

[Insights Discovered](#insights_discovered)

[Power BI Dashboard](#power_bi_dashboard)

[Summary Excel Table](#summary_excel_table)

[SQL Queries](#sql_queries)

[Data Summary](#data-summary)

[Recommendation](#recommendation)

[Conclusion](#conclusion)


### Project Overview
---
This report is to gain insights into sales performance,product demand, and customer behavior using real-world data analytics tools

### Data Source
---
The dataset for this analysis was gotten from kaggle

### Tools Used
---
- SQL Server (Data cleaning & querying)
- Microsoft Excel (Initial exploration & summary tables)
- Power BI (Interactive dashboard & visual stroytelling)

### 📊 Key Buisness Questions
---
- What are the top selling items?
- Which month generated the most revenue?
- What payment method is most popular?
- How do takeaway vs indoor services compare?

### 🧹 Data Cleaning
  ---
  Performed in Excel and SQL:
  - Remove blank and replace invalid rows with **Not Avialable**
  - Standardized column names
  - Fixed data types (dates, numbers)
 
 ### 🧠 Insights Discovered
  ---
  - **Juice** was the top-selling quantity by item
  - **January** had the highest revenue across all months
  - Although **Not Available** appeared most frequently used payment method (due to missing or unrecorded data), **Credit Card** emerged as the most used payment method
  - **Not Available** appeared was the most common entry in the service mode , indicating missing or unrecotded data. excluding these, **Takeaway** was the most frequent service mode
 
## 📈 Power BI Dashboard
---
![image](https://github.com/user-attachments/assets/cc08e8f7-3d26-416f-919e-cba43e27752a)

![image](https://github.com/user-attachments/assets/992f8546-3f17-43b0-9812-b3b71e87d6f1)

![image](https://github.com/user-attachments/assets/5ff1cbf7-4838-4a93-aca9-2b047ebdd9e1)

![image](https://github.com/user-attachments/assets/ea7c6f9d-c494-46d9-a011-7bc291540d23)

Includes:
- Total price
- Sales by item
- Quantity by item
- Service mode comparison

## 📋 Excel Table
---
![image](https://github.com/user-attachments/assets/485783cf-ddf2-40b8-9713-dd163b42a606)

![image](https://github.com/user-attachments/assets/c2a0e037-3470-4fd1-80b7-5ec119f9f555)

![image](https://github.com/user-attachments/assets/8197d76a-c518-415b-af6a-fbe3775da84f)

![image](https://github.com/user-attachments/assets/85d68076-44f9-4249-8cda-8bb29cd077f8)

![image](https://github.com/user-attachments/assets/580e6ad7-b763-4975-b7af-8cfcfa6a2ced)

![image](https://github.com/user-attachments/assets/bb89a186-3f7e-409b-91ba-87550048ef8e)

![image](https://github.com/user-attachments/assets/3ef32f19-7941-4003-94ee-602b3bdd5592)

![image](https://github.com/user-attachments/assets/84e22914-124c-4609-a43e-213a382a9cf8)

![image](https://github.com/user-attachments/assets/d5d47d55-ba5b-484f-a9d7-669f65e5b838)

Includes:
- Summary table
- Pivot table
- Pivot chart

## 💾 SQL Queries
---
![image](https://github.com/user-attachments/assets/acefde1c-81cc-4b5d-a46b-20f280499afd)

![image](https://github.com/user-attachments/assets/1dc71dd7-0181-4968-907e-71ffca6bee7b)

![image](https://github.com/user-attachments/assets/2fe4c796-2987-4ac7-adcd-cbd23cbf8628)

![image](https://github.com/user-attachments/assets/583698c7-74bb-4567-8a77-a9ed1921a218)

![image](https://github.com/user-attachments/assets/4af50c0f-38f3-4f6b-b728-abe7c99dfb0d)

![image](https://github.com/user-attachments/assets/94cad222-b023-48d2-a7ae-022369c32abf)

![image](https://github.com/user-attachments/assets/4e19d5a4-9b40-4d4d-8221-982357a75ce2)

![image](https://github.com/user-attachments/assets/e6f790a8-9cf4-41e6-bc96-6112cfed573d)

![image](https://github.com/user-attachments/assets/732fe3d4-8d7b-4fb7-8bdd-202d68f81146)

![image](https://github.com/user-attachments/assets/c4b2dc7d-6942-496e-a31c-c8b677b8cda0)

![image](https://github.com/user-attachments/assets/7c29c863-a3ba-40c6-887d-9801d91ac771)

![image](https://github.com/user-attachments/assets/2f8e5322-3dfd-4c93-9ed1-8b3f80e96bac)

## 📊 DATA SUMMARY
---
The dataset contains transactional records from a cafe, including details such as:
- Item purchased
- Quantity sold
- Total price
- Transaction date
- Payment method (e.g card, cash, or digital wallet)
- Service mode (e.g. takeaway, or in-store)

## Key observations from the analysis:
- Over 10,000 rows of data were imported, cleaned, and analyzed using SQL, Excel, and Power BI.
- Several records had missing or unrecorded payment methods, represented as "Not Available".
- The top-selling item by quantity was Juice, while January recorded the highest overall revenue.
- Excluding missing values, Credit Card was the most common payment method.
- Takeaway was the most frequently used service mode.

## 🔍 Recommendations
---
# Enhance Data Quality
- Implement mandatory logging for Payment_Method and Service_Mode fields to avoid "Not Available" entries.
- Apply data validation rules directly in the point-of-sale system to minimize user input errors.
# Leverage Seasonal Insights
-Investigate drivers behind the January revenue spike (e.g., promotions, holidays) and replicate those strategies in low-performing months.
# Optimize Inventory Management
-Prioritize stock and promotion of high-volume products like Juice to avoid shortages and maximize ROI.
# Payment Infrastructure
- Since Credit Card is the most preferred valid method, optimize and expand card payment channels (e.g., POS terminals, QR codes, or app payments).




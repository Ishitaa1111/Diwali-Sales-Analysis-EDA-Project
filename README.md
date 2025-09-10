
#  Diwali Sales Data - Exploratory Data Analysis



## 📌 Table of Contents  
1. [Project Overview](#1-project-overview)  
2. [Business Problem / Objective](#2-business-problem--objective)  
3. [Dataset Description](#3-dataset-description)  
4. [Tools & Skills Used](#4-tools--skills-used)  
5. [Approach / Methodology](#5-approach--methodology)  
6. [Key Insights / Results](#6-key-insights--results)  
7. [Dashboard / Output Screenshots](#7-dashboard--output-screenshots)  
8. [Conclusion & Future Work](#8-conclusion--future-work)  



## 1. Project Overview
This project delivers a comprehensive **Exploratory Data Analysis (EDA)** on Diwali Sales Data, consisting of **11,239 customer transactions across 12 attributes**.  
The analysis focuses on uncovering **customer demographics, purchasing behavior, product preferences, and regional trends**, enabling businesses to make **data-driven marketing, sales, and inventory decisions**. By leveraging **Python, Pandas, NumPy, and Matplotlib**, the study identifies the most valuable customer segments, high-performing states, and top product categories.  
The insights derived are directly applicable to **targeted marketing strategies, revenue optimization, customer segmentation, and campaign planning**, making it highly relevant for **business analysts, data analysts, and decision-makers**.  


## 2. Business Problem / Objective
The analysis focuses on enhancing sales performance and customer engagement by:

* Identifying key demographics: Gender, Age, Marital Status  
* Determining top-performing states & occupations  
* Recognizing high-demand product categories  
* Understanding demographic-purchasing behavior relationships  



## 3. Dataset Description
**Rows:** 11,239 | **Columns:** 12  
**Key Attributes:**  

| Attribute | Description |
|-----------|-------------|
| User_ID | Unique customer identifier |
| Cust_name | Customer name |
| Product_ID | Unique product identifier |
| Gender | Male / Female |
| Age Group | Customer age group |
| Age | Exact age |
| Marital_Status | 0 = Married, 1 = Unmarried |
| State | Customer's state |
| Zone | Geographical zone |
| Occupation | Customer occupation |
| Product_Category | Purchased product category |
| Orders | Number of orders |
| Amount | Total transaction value |



## 4. Tools & Skills Used
 
### Programming Language  
- **Python**  

### Libraries  
- **Pandas** → For data manipulation, cleaning, and analysis  
- **NumPy** → For numerical operations  
- **Matplotlib → For creating a wide range of static, animated, and interactive visualizations  

###  Skills  
- **Data Cleaning and Preprocessing** → Handling missing values, and correcting data types  
- **Exploratory Data Analysis (EDA)** → Using descriptive statistics and visualizations to understand the data  
- **Data Visualization** → Creating informative and visually appealing charts and graphs to communicate findings effectively  




## 5. Approach & Methodology
The analysis followed a **structured methodology** to ensure accurate and actionable insights:  

###  Data Loading & Initial Inspection  
- The **"Diwali Sales Data.csv"** file was loaded into a Pandas DataFrame.  
- An initial inspection was performed to understand the structure, data types, and presence of missing values.  

###  Data Cleaning  
- Unnecessary columns (**'Status'**, **'unnamed1'**) were removed.  
- Rows with missing values were dropped to ensure data quality.  
- The **'Amount'** column was converted to an integer data type for numerical analysis.  

###  Exploratory Data Analysis (EDA)  
- A comprehensive **EDA** was conducted to explore relationships between variables.  
- Grouping and aggregation were performed to analyze sales patterns across demographics and product categories.  

###  Data Visualization  
- Visualizations were created using **Matplotlib** and **Seaborn**.  
- These plots provide a clear and concise representation of the key insights discovered during EDA.  


## 6. Key Insights / Results


###  Gender Analysis  
- **Female buyers = 7,832 vs Male buyers = 3,407**  
- **Revenue:**  
  - Females → `$74,335,853`  
  - Males → `$31,913,276`  
 *Women are 2.3× more valuable → female-focused marketing recommended*  



###  Age Group  
- **26–35 years = highest buyers + sales contribution**  
 *Prime target segment for festive promotions*  



###  Marital Status  
- Married → `$62,125,384`  
- Unmarried → `$44,123,745`  
   *Married customers dominate spending patterns*  



### Top States by Sales  
1. Uttar Pradesh  
2. Maharashtra  
3. Karnataka  
 *Focus sales & campaigns in these high-value regions*  



###  Occupation Analysis  
**Top 3 spenders:**  
1. IT Sector  
2. Healthcare  
3. Aviation  
    *These sectors = high disposable income groups*  



### Product Categories  
- Food, Clothing & Apparel, Electronics & Gadgets dominate sales  
 *Prioritize these for promotions & stock planning*  



## 7. Dashboard / Output Screenshots



<img width="700" height="500" alt="Code_Generated_Image (8)" src="https://github.com/user-attachments/assets/dc9f0c6b-c142-44f6-828e-5a59f125292b" />
<img width="700" height="500" alt="Code_Generated_Image (9)" src="https://github.com/user-attachments/assets/c2234ef7-a6d6-47f5-b100-35c878f680b1" />
<img width="1600" height="480" alt="Code_Generated_Image (1)" src="https://github.com/user-attachments/assets/44655dae-b4d2-49c4-ad97-a19b32d4b9cd" />
<img width="1500" height="600" alt="Code_Generated_Image (2)" src="https://github.com/user-attachments/assets/869ad4a2-27cb-4129-9ade-193f748e86d3" />
<img width="1500" height="600" alt="Code_Generated_Image (3)" src="https://github.com/user-attachments/assets/c6036c87-204f-4327-b89f-a61cd5090591" />
<img width="1000" height="500" alt="Code_Generated_Image (4)" src="https://github.com/user-attachments/assets/44911874-6ccd-4c32-97fc-0b2a3c1eb906" />
<img width="1200" height="600" alt="Code_Generated_Image (5)" src="https://github.com/user-attachments/assets/f340476d-061d-41d6-af77-b6cd6ec09670" />
<img width="1200" height="600" alt="Code_Generated_Image (6)" src="https://github.com/user-attachments/assets/61039821-23d1-48e9-90e0-42cc821cc52b" />
<img width="1000" height="500" alt="Code_Generated_Image (7)" src="https://github.com/user-attachments/assets/026e0c53-5baa-4b0e-bac2-998ec3e3f2dd" />

## 8️. Conclusion & Future Work  

**Conclusion:**  
* The analysis highlights that the **primary customer segment** during Diwali sales is **married women aged 26–35**, mainly from **Uttar Pradesh, Maharashtra, and Karnataka**.  
* The most purchased categories are **Food, Clothing & Apparel, and Electronics**, making them key drivers of festive revenue.  
* These insights enable **targeted marketing campaigns, optimized inventory stocking, and tailored promotions** to maximize customer engagement and sales performance.  

**Future Work:**  
* **Customer Segmentation** → Apply clustering to create detailed customer personas for highly personalized marketing.  
* **Product Recommendation Engine** → Suggest complementary products based on purchase history to increase average order value.  
* **Sentiment Analysis** → Analyze customer reviews and feedback for deeper insights into preferences and pain points.  
* **Time Series Forecasting** → Predict seasonal trends and sales demand for future Diwali campaigns to ensure proactive business planning.  



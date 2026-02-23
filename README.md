## UNCOVERING THE POWER SPENDER: A DEEP DIVE INTO CUSTOMER BEVIOUR ACROSS REGIONS AND AGE

### EXECUTIVE SUMMARY 
This analysis explores customer spending across demographics, regions, and time periods. It identifies young adults and UK buyers as the top revenue contributors, with most transactions made at full price using credit cards. Sales peak in Q4 2024 and Q1 2025, highlighting key periods for targeted marketing and optimized payment experiences, while selective discounts could further boost spending.

### GOAL
Which groups of people (by country and age) spend the most money, and how do their habits change if they use different ways to pay or get a discount throughout the year?

### PROCESS
1. **Collected the dataset**
   [Here](https://github.com/Morire-Adeniran/Uncovering-the-Power-Spenders/blob/main/_counterfeit_transactions%20-%20Copy.xlsx)

3. **Cleaned the data**
* Removed outliers from the transaction date column 
* Handled duplicates

3. **Transformed the data**
* Created new columns;YEAR and MONTH from the transaction date column using the function TEXT
* Grouped Customer Age into Standard Age Label 
* Grouped Discount percentage into ranges i.e Low, Medium,High and No discount 

4. **Analyzed the data**
   
* Calculated key metrics
  - Gross Sales=Price × Quantity
  - Net Sales= Gross Sales - Discount
* Identified top customers by net sales(From the age group and country)  
* Computer month over month trends to identify seasonal patterns 
Compared payment method performance 

5. **Visualized  the data**
* Bar Chart: Sales by Age group 
* Column Chart: Sales by Region 
* Line Chart: Monthly Sales Trends 
* Bar Chart: Sales by Payment Method 

![Dashboard](https://github.com/Morire-Adeniran/Uncovering-the-Power-Spenders/blob/main/_counterfeit_transactions%20-%20Copy%20-%20Dashboard.png)

### SKILLS
Excel: Pivot tables, Scenario Analysis,Conditioning formatting, Dashboard 



### KEY INSIGHT 
1. 𝗧𝗼𝗽 𝗦𝗽𝗲𝗻𝗱𝗲𝗿𝘀 𝗯𝘆 𝗔𝗴𝗲 𝗮𝗻𝗱 𝗖𝗼𝘂𝗻𝘁𝗿𝘆

Young Adults contribute the highest share with 20.37% of total sales.

The UK leads all countries with 10.7% of total revenue.

2. 𝗣𝗮𝘆𝗺𝗲𝗻𝘁 𝗠𝗲𝘁𝗵𝗼𝗱 & 𝗗𝗶𝘀𝗰𝗼𝘂𝗻𝘁 𝗕𝗲𝗵𝗮𝘃𝗶𝗼𝘂𝗿

Young Adults and UK customers mostly use credit cards and often pay full price.

More than 75% of all transactions occur without discounts, showing strong willingness to pay full value.

3. 𝗛𝗼𝘄 𝗧𝗵𝗲𝗶𝗿 𝗛𝗮𝗯𝗶𝘁𝘀 𝗖𝗵𝗮𝗻𝗴𝗲 𝗧𝗵𝗿𝗼𝘂𝗴𝗵𝗼𝘂𝘁 𝘁𝗵𝗲 𝗬𝗲𝗮𝗿

Credit cards are used the most in Q1 and Q3, while PayPal usage rises in Q2 and Q4.

Full-price buying peaks in Q4, while high-discount purchases rise in Q3.

Sales peak in Q4 2024 (26.86%) and Q1 2025 (25.57%), showing strong start- and end-of-year demand.

### RECOMMENDATIONS 

1. 𝗧𝗮𝗿𝗴𝗲𝘁 𝘁𝗵𝗲 𝗥𝗶𝗴𝗵𝘁 𝗖𝘂𝘀𝘁𝗼𝗺𝗲𝗿𝘀 𝗮𝘁 𝘁𝗵𝗲 𝗥𝗶𝗴𝗵𝘁 𝗧𝗶𝗺𝗲
   
Focus campaigns on Young Adults and UK customers during Q1 and Q4, when spending is highest.

2. 𝗔𝗱𝗷𝘂𝘀𝘁 𝘁𝗵𝗲 𝗣𝗮𝘆𝗺𝗲𝗻𝘁 𝗘𝘅𝗽𝗲𝗿𝗶𝗲𝗻𝗰𝗲 𝗯𝘆 𝗦𝗲𝗮𝘀𝗼𝗻

Optimize credit-card checkout for Q1 and Q3, and ensure PayPal flow is smooth for Q2 and Q4, since customer preference shifts by quarter.

3. 𝗨𝘀𝗲 𝗦𝗺𝗮𝗿𝘁 𝗦𝗲𝗮𝘀𝗼𝗻𝗮𝗹 𝗗𝗶𝘀𝗰𝗼𝘂𝗻𝘁𝗶𝗻𝗴
   
Push bigger discounts in Q3 because customers respond more then.

Reduce discounting in Q4 and focus on full-price premium offerings, since customers naturally pay more during that period.

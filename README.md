# 📊 Online Retail Sales Performance Dashboard  
**Tata Data Visualisation: Empowering Business with Effective Insights**  

This project was developed as part of the **Tata Data Visualisation: Empowering Business with Effective Insights** course on Forage. The objective was to analyze **Online Retail Sales Data**, create insightful **Power BI dashboards**, and present findings to the **CEO** and **CMO** to guide business growth and marketing strategies. The deliverables included data cleaning, visualization, and insights to drive strategic decisions.  

---


## 🗂 Dataset
- **File:** `Online Retail Data Set.xlsx`
- **Description:** Contains transaction-level data including Invoice Number, Stock Code, Product Description, Quantity, Invoice Date, Unit Price, Customer ID, and Country.
- **Time Period:** One year of retail transactions.
- **Source:** Provided as part of the Tata Data Visualisation program.

---

## ✅ Task 1: Framing the Business Scenario
Eight key business questions were developed to align with leadership priorities.

### CEO’s Questions (Operations & Growth)
1. Which countries or regions generate the highest revenue, and where is the business underperforming?
2. What percentage of total revenue is contributed by our top 10% of customers, and how frequently do they purchase?
3. Which product categories or items have the highest return rates, and how does this impact profitability?
4. Are there seasonal or monthly trends in revenue or orders to help optimize inventory and staffing?

### CMO’s Questions (Marketing & Customer Insights)
1. Which customer segments (based on country, frequency, or spend) are most responsive and profitable for targeted campaigns?
2. What is the average customer lifetime value (CLV), and how does it differ across demographics and purchase channels?
3. Which marketing campaigns or promotions have driven the highest sales uplift?
4. What are the common characteristics of customers with high return frequency or low engagement?

---

## ✅ Task 2: Choosing the Right Visuals

**Goal:** Select the most effective chart types for CEO/CMO business questions to ensure clear, accurate insights.

**Steps Taken:**
1. Read and understood each business requirement.
2. Matched data type with the best-fit visual.
3. Used tools like Power BI, Excel, and industry chart guidelines.

**Visual Choices:**
| Question | Visual |
|----------|--------|
| Top revenue countries | Horizontal Bar Chart |
| Top 10% customers’ revenue share | Pareto Chart |
| Highest return rates by category | Clustered Column Chart |
| Monthly/seasonal order trends | Line Chart |
| Conversions by marketing channel | Stacked Bar Chart |

**Result:** Clear visuals for decision-making, highlighting strengths, growth areas, and trends.

---
**Dashboard**



---

## ✅ Task 3 – Creating Effective Visuals

In this task, we created four key visuals requested by the **CEO** and **CMO** of the online retail store using **Microsoft Power BI**.  
The process involved **data cleaning**, **transformations**, and **DAX calculations** to ensure accuracy before building the visuals.  

---

### **Step 1 – Data Cleaning (Power Query)**
Before creating visuals, the dataset was cleaned in **Power Query** to remove invalid records:  
1. **Removed Negative Quantities** – Filtered out rows where `Quantity < 1`.  
2. **Removed Invalid Prices** – Filtered out rows where `UnitPrice <= 0`.  
3. **Ensured Data Types** – Converted columns to the correct data types for accurate aggregation.  

---

### **Step 2 – DAX Measures**
Custom DAX measures were created for accurate analysis:  
- **Total Revenue**  
``DAX
Total Revenue = SUMX( Sales, Sales[Quantity] * Sales[UnitPrice] )
Total Quantity Sold = SUM( Sales[Quantity] )

---


## **Step 3 – Visual Creation**
Each visual was placed on a **separate report page (tab)** in Power BI, with the tab named according to the question number.

---

### **Question 1 – Monthly Revenue Trend (2011)**
- **Visual Type:** Line Chart  
- **Purpose:** Identify seasonal patterns in monthly revenue for the year 2011 and assist in forecasting.  
- **Details:**  
  - **X-axis:** Month  
  - **Y-axis:** Revenue  

---

### **Question 2 – Top 10 Countries by Revenue & Quantity (Excluding UK)**
- **Visual Type:** Clustered Column Chart  
- **Purpose:** Display the top 10 revenue-generating countries (excluding UK) along with quantities sold.  
- **Details:**  
  - Dual bars for **Revenue** & **Quantity**  

---

### **Question 3 – Top 10 Customers by Revenue**
- **Visual Type:** Sorted Bar Chart  
- **Purpose:** Identify high-value customers for targeted retention strategies.  
- **Details:**  
  - Sorted in **descending order** of revenue  

---

### **Question 4 – Global Demand by Country (Excluding UK)**
- **Visual Type:** Map Chart  
- **Purpose:** Visualize demand geographically and identify regions with expansion potential.  
- **Details:**  
  - **Bubble size** represents quantity sold  

---

## **Step 4 – Deliverables**
- 📂 **Power BI File (.pbix)** – Contains cleaned data, DAX measures, and visuals.  
- 📊 **Dashboard** – Interactive view for quick insights.  
- 📄 **Cleaned Excel Data (.xlsx)** – For reference and future use.  

---

## ✅ **Tools Used**
- **Microsoft Power BI** – Data visualization & dashboard creation
- **Power Query** – Data cleaning & transformation
- **Excel** – Dataset storage and exploration
- **DAX (Data Analysis Expressions)** – Calculated measures


---


## ✅ Task 4: Communicating Insights
A 5-minute presentation was prepared for the CEO and CMO summarizing:
- **Approach:** Data loading, cleaning, and transformation steps.
- **Insights:** Focused answers to the 8 strategic questions.
- **Business Recommendations:**
  - Invest more in top-performing countries outside the UK.
  - Target high-value customers with loyalty programs.
  - Address high return rate products via quality control.
  - Align inventory with seasonal demand.
  - Customize marketing campaigns per customer segment.

---

## 📌 Key Learnings
- Translating business problems into analytical questions.
- Using **Power Query** for robust data preparation.
- Building interactive dashboards in Power BI.
- Presenting actionable insights to non-technical stakeholders.

---

## 📜 Certificate
This project was part of the **Tata Data Visualisation: Empowering Business with Effective Insights** program on Forage.

---

## 👩‍💻 Author
**Anushka Bansal**  
Data Analyst | Business Intelligence Enthusiast | Power BI Developer
Email:[anushkabansalhere@gmail.com]
LinkedIn:[www.linkedin.com/in/anushkabansal13]
Portfolio:[https://www.datascienceportfol.io/anushkabansalhere]

---

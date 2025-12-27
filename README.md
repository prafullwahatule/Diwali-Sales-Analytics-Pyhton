# 🎉 Diwali Sales Analysis

## 📄 Project Overview
This project analyzes **Diwali season sales** to provide actionable insights for business decision-making.  
The goal is to understand **customer behavior, product performance, regional trends, and revenue contribution** to improve **marketing, inventory planning, and loyalty strategies**.

The analysis is performed on a dataset containing the following columns:

---

## Dataset
The dataset contains the following columns:
- `User_ID` – Unique customer ID
- `Cust_name` – Customer name
- `Product_ID` – Product identifier
- `Gender` – Customer gender
- `Age Group` – Age group category
- `Age` – Customer age
- `Marital_Status` – Marital status of customer
- `State` – Customer state
- `Zone` – Geographical zone
- `Occupation` – Customer occupation
- `Product_Category` – Type of product
- `Orders` – Number of orders
- `Amount` – Total spending
- `Status` – Order status
- `Unnamed1` – Extra column (if any)


---

## 🔍 Objectives
1. Identify high-value customers and repeat buyers.
2. Analyze revenue contribution by **customer demographics** (Age, Gender, Occupation).
3. Determine top-selling **product categories** and cross-category buying patterns.
4. Evaluate **regional performance** (State & Zone) and plan inventory accordingly.
5. Provide **revenue forecasting** estimates for the next Diwali season.
6. Generate **business-ready insights and recommendations**.

---

## 📊 Key Findings & Business Solutions

### 1️⃣ Customer Behavior Insights
**Findings:**
- Repeat customers generate more revenue than one-time buyers.
- Top 5% customers contribute a significant share of total revenue.
- Multi-category buyers spend significantly more.

**Business Solutions:**
- Introduce **loyalty programs** and **exclusive offers** for top customers.
- Provide **early Diwali deals** to repeat customers.
- Create **bundle offers and cross-sell campaigns** for multi-category buyers.

---

### 2️⃣ Demographic Insights (Age, Gender, Occupation)
**Findings:**
- Specific age groups and occupations are high spenders.
- High-value customer patterns are consistent.

**Business Solutions:**
- Targeted marketing campaigns based on **age and occupation**.
- Focus **premium products** on high-spending demographics.
- Offer **personalized promotions** for high-value segments.

---

### 3️⃣ Product & Category Performance
**Findings:**
- Certain product categories consistently generate high revenue.
- Frequent cross-category purchases indicate potential for **bundle offers**.

**Business Solutions:**
- Increase **stock of top-performing categories**.
- Launch **combo offers** for popular category pairs.
- Run **discounts/promotions** for low-performing categories.

---

### 4️⃣ Regional Performance (State & Zone)
**Findings:**
- Few states and zones dominate total revenue.
- Each state has different product category preferences.
- Heatmaps show regional demand clearly.

**Business Solutions:**
- Plan **region-wise inventory**.
- Execute **state-specific promotions**.
- Implement **marketing campaigns** in weaker regions.

---

### 5️⃣ Revenue Estimation & Forecasting
**Findings:**
- Dataset lacks time-series data → accurate forecasting is not possible.
- Using growth-based estimation, future Diwali revenue can be predicted.

**Business Solutions:**
- Use **historical revenue + growth assumptions** for budget planning.
- Add **date/year columns** in future datasets for accurate forecasting.

---

### 6️⃣ High-Value Customer Targeting
**Findings:**
- Top 5% customers contribute the majority of revenue.
- Their **product preferences and demographic profiles** are identifiable.

**Business Solutions:**
- Implement **VIP customer programs**.
- Provide **personalized recommendations**.
- Focus on **customer retention** rather than only acquisition.

---

## 🔧 Methodology
1. **Data Cleaning & Preprocessing**
   - Checked for missing values, duplicates.
   - Standardized categorical columns.
2. **Customer Segmentation**
   - Identified repeat vs one-time buyers.
   - Segmented customers into **high, medium, and low spenders**.
3. **Revenue Analysis**
   - Grouped by **customer, product category, state, zone**.
   - Calculated total revenue and top contributors.
4. **Cross-Category Analysis**
   - Identified customers purchasing multiple categories.
   - Found frequent product category combinations.
5. **Visualization**
   - **Bar charts** for top categories, occupations, age groups.
   - **Heatmaps** for state-wise category revenue.
   - Pie charts for revenue share of repeat vs one-time customers.
6. **Forecasting (Proxy)**
   - Predicted next Diwali revenue using **historical total revenue + assumed growth rate**.

---

## 📈 Visualizations Included
- Revenue by **Customer Type** (Repeat vs One-Time Buyers)
- **Top Product Categories** by Revenue
- **Customer Segment Revenue Contribution** (High, Medium, Low Spenders)
- **State-wise Product Category Heatmap**
- **High-Value Customer Preferences** (Category, Age, Occupation)
- Revenue contribution comparison: **Multi-category vs Single-category buyers**

---

## 🧠 Business Recommendations
1. **Focus on high-value customers** for loyalty programs and personalized campaigns.
2. **Increase stock** of top-performing product categories before Diwali.
3. **Use regional insights** for inventory allocation and marketing promotions.
4. Promote **popular category bundles** for cross-selling.
5. **Collect time-series sales data** for accurate forecasting next year.
6. **Retention-focused marketing** for top 5% revenue-generating customers.

---

## ⚡ Conclusion
> “Diwali sales growth can be maximized by focusing on high-value customers, top product categories, and high-performing regions.  
> Personalized marketing, smart inventory planning, and loyalty programs will improve both **revenue and customer retention**.”

---

## 📌 Notes
- All analysis done in **Python** using **Pandas, Seaborn, and Matplotlib**.
- Assumes **historical Diwali sales data** without explicit dates.
- Forecasting is **assumption-based**, not time-series due to missing date data.


---
## 🙏 Acknowledgement  

Special thanks to the **Diwali Sales Sharing Dataset (Open Data)** for providing an excellent real-world dataset.  
This project was created as part of a **Data Analytics learning journey** using **Pandas, Numpy, Seaborn, and Matplotlib**.  

---

## 📎 Author  

**👤 Name:** Prafull Wahatule  
**📧 Email:** [prafullwahatule@gmail.com](mailto:prafullwahatule@gmail.com)  
**💻 GitHub:** [prafullwahatule](https://github.com/prafullwahatule)  

---

⭐ *If you found this project helpful, don’t forget to star the repository!* ⭐

# Retail Analytics & Customer Segmentation

An end-to-end **Data Analytics & Clustering** project using **Python** and **Power BI** to analyze global retail data, understand customer behavior, and segment customers based on **RFM Analysis** and **K-Means Clustering**.

---

##  Objective

- Analyze retail performance across countries, categories, and customer segments.
- Uncover insights related to delivery, profit margin, and order value trends.
- Segment customers based on Recency, Frequency, and Monetary metrics.
- Visualize all business KPIs through a professional **Power BI Dashboard**.

---

## Dataset

- **File**: `Global_Superstore2.xlsx`
- **Source**: Global Superstore sales data
- **Period**: 2011 to 2014
- **Features**:
  - Order Date, Ship Mode, Category, Sub-Category
  - Sales, Quantity, Discount, Profit
  - Country, Region, Segment
  - Customer ID, Customer Name

---

## Tools & Technologies

| Component | Tech Used |
|----------|-----------|
| Data Analysis | Python (Pandas, NumPy) |
| Visualization | Power BI, Matplotlib, Seaborn |
| Machine Learning | Scikit-learn (K-Means, PCA) |
| IDE | Jupyter Notebook |
| Data Cleaning & Export | Excel + Python |

---

##  Project Workflow

### 1. Data Cleaning
- Removed missing and duplicate records.
- Calculated delivery duration (`Ship Date - Order Date`).
- Created RFM scores (Recency, Frequency, Monetary).

### 2. Exploratory Data Analysis (EDA)
- Sales & profit trends by year, country, category, and segment.
- Identified high-growth countries, top-selling segments.
- Delivery performance by ship mode.

### 3. Customer Segmentation
- RFM-based segmentation: Champions, Loyal, At Risk, etc.
- Scaled features using `StandardScaler`.
- Applied **K-Means Clustering** and validated with Elbow Method.
- Reduced dimensionality using **PCA** for 2D cluster visualization.

### 4. Dashboard (Power BI)
- KPIs: Total Sales, Profit Margin, Orders, Avg Order Value
- Sales trends over time
- Global sales performance map
- Sales by segment and RFM label
- Top 10 most profitable products
- Filters: Country, Date, Ship Mode, Category

---

##  Sample Visuals

###  Power BI Dashboard

![Retail Sales Dashboard](dashboard/powerbi_dashboard.png)

This interactive dashboard includes:
-  Total Sales: **$12.46M**
-  Total Orders: **25K**
-  Total Customers: **2K**
-  Avg Order Value: **$505.05**
-  RFM Segment Analysis
-  Sales performance by country
-  Top 10 Most Profitable Products

---

##  Folder Structure

```
Retail_Analytics_Customer_Segmentation/
│
├── data/
│   └── Global_Superstore2.xlsx
├── notebooks/
│   └── retail_analysis_customer_segmentation.ipynb
├── dashboard/
│   └── powerbi_dashboard.png
│   └── powerbi_dashboard.pbix
├── output/
│   └── cleaned_superstore_data.csv
├── README.md
└── requirements.txt
```

---

##  Key Insights

-  Loyal customers contribute the most to customer lifetime value.
-  Technology is the most profitable category globally.
-  North America leads in profit margins.
-  Second Class & Standard Class have longer delivery durations.
-  RFM segmentation helps target marketing to Champions & At-Risk groups.

---

##  Future Improvements

- Automate data pipeline (ETL) using Python or Power Query
- Integrate SQL-based backend and live dashboards
- Predict Customer Lifetime Value (CLV) with supervised ML
- Real-time alerting for at-risk customer churn

---

##  About Me

**Veera Sai Pavan Chavvakula**  
Aspiring Data Analyst | Skilled in Python, SQL, Power BI, and Machine Learning  
 veerasaipavan6673@gmail.com  
 [LinkedIn]( https://www.linkedin.com/in/veera-sai-pavan-chavvakula-6260a72bb )

If you found this project insightful, feel free to ⭐ star this repo or share it!

---

This project is open source and available under the [MIT License](LICENSE).
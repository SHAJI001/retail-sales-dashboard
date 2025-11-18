# Retail Sales Performance Dashboard – Case Study

## 1. Business Problem
A retail operations manager needed a clear, simple way to monitor sales and profit performance across U.S. regions, product categories, and sub-categories. Existing reports were raw spreadsheets, making it difficult to identify trends or underperforming areas quickly.

The goal was to build an interactive Excel/Google Sheets dashboard that summarizes key performance indicators (KPIs), shows regional performance, and highlights top and bottom performing categories.

---

## 2. Dataset
**Rows:** 50  
**Columns:** OrderDate, Region, Category, SubCategory, Sales, Quantity, Profit  
**Source:** Synthetic dataset created for portfolio demonstration.

The dataset simulates real retail transactions including:
- Different regions (East, West, Central, South)
- Categories (Furniture, Technology, Office Supplies)
- Sub-categories (Chairs, Phones, Binders, etc.)
- Transaction-level sales, quantity, and profit

---

## 3. Approach

### **3.1 Data Preparation**
- Validated OrderDate formatting
- Ensured numeric fields contained no errors
- Created helper fields:
  - Year
  - Month
  - Profit Margin (`Profit / Sales`)

### **3.2 Pivot Tables Built**
1. **Sales & Profit by Region**  
2. **Sales & Profit by Category/Sub-category**  
3. **Monthly Sales Trend**  
4. **Top Products by Profit (optional)**  

### **3.3 Dashboard Design**
The dashboard includes:
- KPI cards:
  - Total Sales
  - Total Profit
  - Profit Margin %
- Bar charts for Category & Regional comparisons
- Line chart for monthly trends
- Slicers for Region, Category, and Year

### Tools Used
- Excel or Google Sheets  
- Pivot Tables  
- Charts  
- Basic formulas  

---

## 4. Key Insights (Example Findings)
- **East Region** generated the highest total revenue.  
- **Technology** had the highest overall profitability.  
- **Furniture** showed inconsistent margins due to shipping and returns.  
- Sales increased in Q1, especially for laptops and accessories.  

---

## 5. Business Outcomes
The final dashboard provides:
- One-page visual summary for managers  
- Interactive filtering  
- Clear visibility into high- and low-performing areas  
- Data-driven insights for promotional and inventory planning  

---

## 6. What I Learned
- How to structure data for pivot tables  
- Designing a simple, business-friendly dashboard  
- Summarizing insights into clear business language  
- Turning raw data into actionable reporting tools  

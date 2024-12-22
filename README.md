---

# **XGRIP Sales and Profit Analytics Dashboard**  

## **Dashboard Screenshots**  

### **Light and Dark Executive Dashboard**  
![Light and Dark Mode](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/light%20dashboard.png)  


### **Sales Overview Dashboard**  
![Sales Overview](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/dark%20dashboard.png)  

### **Product Analysis Dashboard**  
![Product Analysis](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/product.png)  

### **Map Analysis Dashboard**  
![Map Analysis](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/dark%20map.png)  


---

## **Objective**  
The goal of this project was to develop an interactive, user-friendly analytics dashboard for XGRIP, a company specializing in mobile phone accessories. The dashboard provides insights into sales, profits, product performance, and returns while addressing specific data challenges such as multi-source integration and currency standardization.  

---

## **Project Overview**  

### **Key Features**  
- Integration of diverse data sources (PostgreSQL, MySQL, Excel, CSV, and PDF).  
- Currency standardization using USD conversion for consistent reporting across countries.  
- Profitability analysis incorporating COGS, discounts, and quantities.  
- Interactive dashboards with slicers, custom panes, and drillthrough buttons for detailed analysis.  
- Scheduled data refresh using Power BI Gateway for seamless updates.  
- Advanced DAX calculations for KPIs like revenue, profit margin, and YoY sales growth.  
- Implementation of Row-Level Security (RLS) to secure sensitive data.  

### **Technology Stack**  
- **Data Sources:** PostgreSQL, MySQL, Excel, CSV, PDF.  
- **Tools:** Power BI, Power Query, DAX.  
- **Gateway:** Power BI Gateway for scheduled refresh.  

---

## **Step-by-Step Execution**  

### **1. Data Integration**  
- Connected to multiple data sources:  
  - PostgreSQL (cloud-hosted sales data).  
  - MySQL (local warehouse data).  
  - Excel, CSV, and PDF files for supplementary data like currency rates.  
- Used **Power Query** for data cleaning, transformation, and merging.  

### **2. Data Standardization**  
- Standardized sales data from various countries by converting local currency to USD using provided exchange rates.  
- Ensured consistent units for analysis by normalizing data metrics.  

### **3. Data Modeling**  
- Established relationships between tables for unified modeling (star schema).  
- Merged COGS and product data using Power Query to calculate profits.  
- Incorporated discount percentages and quantities for precise metrics.  

### **4. Dashboard Design**  
- Created an interactive dashboard with:  
  - **Light/Dark Modes** using buttons.  
  - Multi-page navigation for **sales overview**, **product analysis**, and **returns insights**.  
  - Visuals: Donut charts, bar charts, map visuals, radar charts, slicers, and matrix tables.  
  - Drillthrough buttons for deep-dives into top products and returns analysis.  
- Added slicer custom panes for better interactivity and filtering.  

### **5. Advanced Calculations**  
- Developed multiple DAX measures:  
  - Revenue, profit, and profit margin.  
  - Target sales based on last month's performance.  
  - YoY growth and sales trends.  

### **6. Automation and Security**  
- Implemented scheduled data refresh via Power BI Gateway to handle new data streams automatically.  
- Configured Row-Level Security (RLS) to restrict data access based on user roles.  

---

## **Final Output**  

### **Screenshots**  
### **Sales Overview Dashboard**  
![Sales Overview](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/dark%20dashboard.png)  

### **Product Analysis Dashboard**  
![Product Analysis](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/product.png)  

### **Map Analysis Dashboard**  
![Map Analysis](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/dark%20map.png)  

### **Light and Dark Mode Example**  
![Light and Dark Mode](https://github.com/najirh/XGRIP-Power-BI-Executive-Dashboard/blob/main/light%20dashboard.png)  


---

## **Key Learnings**  
- **Multi-Source Integration:** Learned how to connect and unify data from various formats and platforms effectively.  
- **Advanced Data Transformation:** Enhanced proficiency in Power Query for cleaning, merging, and transforming data.  
- **DAX Proficiency:** Improved skills in creating complex measures for dynamic KPIs and insights.  
- **Interactive Design:** Gained experience in building user-friendly, visually appealing dashboards with interactivity.  
- **Automation and Security:** Mastered scheduled data refresh and implementing RLS for secure and efficient data handling.  

---

## **Access the Dashboard**  
Explore the live dashboard here: **[Link to Online Reports Page](https://app.powerbi.com/view?r=eyJrIjoiMDE5N2U2ZTAtZDA2Zi00MDgyLWI0MjMtZTlkYjc1ODc0MWVkIiwidCI6ImY3NDM5NmYzLTgwMTUtNGI3NC1iNDY4LWNkYTA0NTEzZDg0YyJ9)**  

---

### **How to Use the Dashboard**  
1. Use slicers to filter data by region, product category, or time period.  
2. Navigate between pages using bookmarks and buttons.  
3. Drillthrough on products or returns charts for detailed insights.  
4. Toggle between light and dark modes for your viewing preference.  

---

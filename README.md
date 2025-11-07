# ☕ Bright Coffee Shop Sales Analysis

### 🚀 Project Overview
This project analyzes historical sales data from **Bright Coffee Shop** to uncover key business insights for the newly appointed CEO.  
As a **Junior Data Analyst**, the goal was to identify top-performing products, peak sales hours, and trends that can help increase revenue and operational efficiency.

---

### 🎯 Objectives
- Determine which products generate the most revenue.  
- Identify peak and off-peak sales hours.  
- Analyze sales trends by product type and time intervals.  
- Recommend strategies to improve sales performance.

---

### 🧠 Key Insights
- **Top Products:** Coffee beverages (Cappuccino, Latte, Espresso) drive the highest revenue.  
- **Peak Hours:** 7:00 AM – 10:30 AM and 3:00 PM – 5:00 PM are the busiest times.  
- **Low Sales Periods:** Evenings show the lowest sales — opportunity for loyalty offers.  
- **Customer Behavior:** Morning customers prefer coffee; afternoon customers choose snacks and desserts.  
- **Stock & Operations:** High-demand items should be restocked frequently during morning peaks.

---

### 🛠️ Tools & Technologies
| Category | Tools Used |
|-----------|-------------|
| **Data Processing** | Snowflake, MySQL Workbench, Google BigQuery |
| **Data Visualization** | Power BI, Tableau, Excel, Google Sheets |
| **Planning & Design** | Miro, Canva, Microsoft PowerPoint |
| **Languages** | SQL, Excel Formulas |

---

### 📊 Data Workflow
1. **Data Planning (Miro)**  
   - Designed data architecture showing sources, ETL pipeline, and visualization flow.
2. **Data Processing (Snowflake)**  
   - Cleaned and transformed data:  
     - Converted price strings (e.g., “3,1” → 3.1).  
     - Created `total_amount = unit_price * transaction_qty`.  
     - Grouped transactions into 30-minute or hourly buckets.
3. **Data Analysis (Excel / Power BI)**  
   - Created pivot tables and dashboards for:
     - Revenue by product category  
     - Sales by time interval  
     - Best-selling and underperforming products
4. **Presentation to CEO**  
   - Delivered insights and strategic recommendations using PowerPoint visuals.

---

### 📈 Results & Recommendations
- Focus marketing on **morning and afternoon peaks**.  
- Launch **bundled deals** for low-performing items.  
- Implement **automated daily sales dashboards**.  
- Introduce **loyalty programs** during off-peak hours.  
- Prepare to scale analysis for **multi-location tracking**.

---

### 📂 Deliverables
- `Miro_Diagram.png` – Data flow and architecture.  
- `Processed_Data.xlsx` – Cleaned dataset with pivot tables and charts.  
- `SQL_Scripts.sql` – Transformations and queries.  
- `Bright_Coffee_Sales_Presentation.pptx` – Executive presentation for CEO.  

---

### 👨‍💻 Author
**Your Name**  
Junior Data Analyst | Data Visualization Enthusiast  
📧 andynoludwe@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/andisiwe-noludwe-6829a616a/?trk=opento_sprofile_details) • [Portfolio](https://github.com/andynoludwe)

---

### 🧩 Future Enhancements
- Automate ETL pipelines using Snowflake Tasks or Python scripts.  
- Add Power BI dashboards with real-time refresh.  
- Incorporate machine learning models to forecast daily sales and optimize inventory.

---

### 📜 License
This project is for educational purposes under the **BRIGHTLEARN Data Analytics Program**.  
Feel free to fork, modify, and reference it with attribution.

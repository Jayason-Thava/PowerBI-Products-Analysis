# 📊 Power BI Project: Product Sales Analysis Dashboard  

This Power BI project focuses on analyzing product sales data using **Power Query for data cleaning and transformation**, followed by visualization in **Power BI Desktop** using interactive charts and maps.

---

## 🎯 Project Goals  
- Clean and transform product dataset using **Power Query Editor**  
- Use **data modeling** and apply transformations (remove/correct/add columns)  
- Create **interactive dashboards** using Power BI Desktop  
- Identify **top-performing products, regions, and profit trends**

---

## 🛠 Skills & Features Practiced

| Category | Skills Gained |
|----------|---------------|
| Data Cleaning | Remove duplicates, filter rows, replace values |
| Data Transformation | Created custom columns, changed data types, added calculated measures |
| Power Query | Applied steps, renamed, filtered, and reshaped data |
| Visualization | Bar Chart, Clustered Bar Chart, Geographic Map |
| Formatting | Used themes, tooltips, data labels, legends & slicers |

---

## 🔧 Data Preparation (Power Query)

In Power BI Query Editor, the following data transformation steps were performed:

✔ Removed unnecessary columns (e.g., IDs, blanks, nulls)  
✔ Corrected data types (Text → Number, Date, Currency)  
✔ Used Replace Values to fix data formatting issues  
✔ Added a Calculated Column LineTotal = [Order_Details.UnitPrice] * [Order_Details.Quantity]  
✔ Filtered data to exclude missing or incomplete records  
✔ Renamed columns for clarity and consistency  


---

## 📈 Visualizations Created in Power BI Desktop

### 1️⃣ Bar Chart – Sum of Quantity by ProductName
- Shows quantity of products  
- Helps identify the best-selling products  
- Visualizes product ranking using bar lengths

  <img width="500" height="250" alt="image" src="https://github.com/user-attachments/assets/74af631d-61ad-4750-a06e-76d996bbca0a" />


---

### 2️⃣ Clustered Bar Chart – Sum of LineTotal by OrderDate  
- Displays **Sales (LineTotal) across different Order Dates**  
- Helps identify **peak sales periods and seasonal trends**  
- Useful for analyzing monthly or yearly performance patterns 

<img width="550" height="315" alt="image" src="https://github.com/user-attachments/assets/b9efc1bb-e0f2-4197-ab1d-231d3a9430c1" />


---

### 3️⃣ Geographic Map – Sum of LineTotal by ShipCountry  
- Shows **total sales (LineTotal) grouped by ShipCountry**  
- Helps identify **top-performing regions across the world**  
- Bubble sizes represent **total sales volume per country**  
---
<img width="750" height="250" alt="image" src="https://github.com/user-attachments/assets/962a82d3-cbf7-4696-83c5-c57696a9b50d" />

## 📂 Dataset Files

| File | Description |
|------|-------------|
| `Products.xlsx` | Raw product sales dataset |
| `Products.pbix` | Power BI dashboard report |

---

## 📸 Dashboard Preview  
<img width="1110" height="627" alt="image" src="https://github.com/user-attachments/assets/00b2b0b5-c8fb-49f7-a467-640b4bb4a0d5" />
  
Example:  
```markdown
https://app.powerbi.com/view?r=eyJrIjoiOTljNTE0MWQtYjdmMC00YzdiLWFlOWUtN2E2YTQ1ZTkwZjZkIiwidCI6IjNlYTdjMTI4LWM2MDEtNDQ3OS1hMDAzLWUxNGQwMGMwYjVjYiJ9

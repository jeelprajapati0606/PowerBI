# 📊 Power BI Project: Sales & Performance Dashboard

## 🔍 Project Overview
This project focuses on building a **Sales and Performance Dashboard** using **Power BI**.  
It includes data modeling, DAX calculations, time intelligence, interactive visuals, and security setup for regional managers.

---

## 🧩 1. Data Modeling
- Created relationships between **Fact** and **Dimension** tables using **Primary & Foreign Keys**  
- Hid unnecessary fields from the report view  
- Maintained a clean **Star Schema** layout with consistent naming conventions  

 <img width="1040" height="639" alt="image" src="https://github.com/user-attachments/assets/1806555a-a60a-4eed-8f61-dcbe3e0951b3" />

---

## 🧮 2. DAX Measures & Calculated Columns
- Built measures using:
  - `CALCULATE`, `FILTER`, `ALL`, `SUMX`, `COUNTX`, `AVERAGEX`
  - `SWITCH` for KPI classification  
  - `RELATED` for joining values
 
- Created calculated columns for:
  - Profit margin classification  
  - Customer full names (First + Last)
    <img width="567" height="42" alt="image" src="https://github.com/user-attachments/assets/5c4556ca-6c7a-4da1-b76d-e9d1893f400c" />
  
  - Year-Month formatting
    
    <img width="441" height="36" alt="image" src="https://github.com/user-attachments/assets/95f27124-5360-4938-b648-e8c3705acda3" />

---

## ⏱️ 3. Time Intelligence
- Implemented **YOY**, **MOM**, and **YTD** calculations for sales and returns  
- Identified **seasonal trends** using time-based visuals
   
<img width="877" height="378" alt="image" src="https://github.com/user-attachments/assets/ee032012-0752-455a-84b3-1b6815a1ac23" />


---

## 📈 4. Dashboard Layout

### 🖥️ Main Page (Dashboard Page)
- Overview of **Sales Performance**  
- KPI Cards for Revenue, Profit, and Returns  
- Trend lines and forecasts for overall sales  
- Top N Products and Top N Customers displayed

<img width="978" height="699" alt="image" src="https://github.com/user-attachments/assets/678d224b-6176-4b0f-b405-a34306005346" />

### 📑 Detail Pages
- **Detail Page 1:** Product Analysis  
  - Bar Charts, Donut Charts for product categories  
  - Matrix with conditional formatting for product-level insights

   <img width="970" height="551" alt="image" src="https://github.com/user-attachments/assets/cbb0d3bb-fa6a-417e-85c6-9285f808cae2" />

- **Detail Page 2:** Customer Analysis  
  - Line Charts and KPI Cards for customer segments  
  - classification and customer full names
    
<img width="971" height="690" alt="image" src="https://github.com/user-attachments/assets/14edf760-7022-48dd-b710-c6e0d3f5d3fd" />


### 🔍 Drillthrough Page
- Individual **Date** view   
- Drillthrough filters applied for focused analysis  

<img width="626" height="371" alt="image" src="https://github.com/user-attachments/assets/ab7f72ca-2122-45ee-9765-4295cfcc0aab" />

---

## 🎛️ 5. Filtering & Interaction
- Added **Slicers** for Product, Customer Segment, Region, and Date  
- Used **Drill Up/Down** and **Drillthrough filters**  
- Implemented **Numeric Range Parameters** for custom filtering  

---

## 🧭 6. Navigation & UX
- Added **Custom Buttons & Bookmarks** for page navigation  
- Built a collapsible **Slicer Panel** for better user experience  
- Enabled **Tooltips** with mini visual summaries  
- Applied **Advanced Conditional Formatting** in Matrix/Table views  

---

## 🔐 7. Security
- Added **Roles for Region Managers**  
- Simulated **Row-Level Security (RLS)** to restrict data by region
  
<img width="1240" height="535" alt="Screenshot 2026-04-29 115632" src="https://github.com/user-attachments/assets/899c5a9f-2e03-432a-ab5d-b87acfd4f252" />
 

---



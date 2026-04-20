# Power BI DAX Project :- DAX DEPO

## 📌 Project Overview
This project leverages **Power BI’s DAX (Data Analysis Expressions)** language to build calculated insights on a **Sales and Returns model**.  
All results are displayed in **Matrix visuals only**, grouped by **Region, Month, Product Category, and Customer Segment**.

---

## 📁 Dataset Tables
The following tables are required:
- `Sales_Fact`
- `Returns_Fact`
- `Customer_Dim`
- `Product_Dim`
- `Date_Dim`
- `Region_Dim`

---

## 🧮 Calculated Columns
1. **Profit** = `SalesAmount - Cost` (in `Sales_Fact`)
2. **ReturnFlag** = `"Returned"` or `"Not Returned"` (in `Sales_Fact`)
3. **Customer Full Name** = `FirstName + LastName` (in `Customer_Dim`)

<img width="1019" height="834" alt="image" src="https://github.com/user-attachments/assets/af0e0e5e-04ce-42b5-8ab1-b8c657c62293" />

---

## 📊 Measures
- Total Sales  
- Total Cost  
- Total Profit  
- Return Rate (% of items returned)  
- Average Sale per Transaction  

<img width="1165" height="502" alt="image" src="https://github.com/user-attachments/assets/c6dc98cd-ac7a-491b-aa10-8f6d0aa3bb0c" />

---

## 🎯 Quick Measures
- Year‑Over‑Year Sales Growth  
- Difference between Current and Previous Month Sales  

<img width="756" height="282" alt="image" src="https://github.com/user-attachments/assets/1eae3451-efba-448e-8e6c-09e2e34926bd" />

---

## 📁 Measure Management
- Create a **Dedicated Measure Table** to organize all DAX measures clearly.

<img width="285" height="669" alt="image" src="https://github.com/user-attachments/assets/3d10f735-b9f4-4087-8465-082c259bf5cf" />

---

## 🔍 Filter Context & Behavior


Use Matrix to compare Sales by Region with and without filters using:
- `ALL()`
- `FILTER()`
- `CALCULATE()`

<img width="789" height="191" alt="image" src="https://github.com/user-attachments/assets/89fcfbf5-0278-447f-9f8c-c698bdfccd9c" />

---

## 📘 DAX Operators and Functions


- Math/statistics: `SUM`, `AVERAGE`, `MAX`  
- Counting: `COUNTX`, `DISTINCTCOUNT`

 <img width="1213" height="407" alt="image" src="https://github.com/user-attachments/assets/2b9a06df-a9a6-4c61-a16c-717f4d7c4795" />

- Conditional logic: `IF`, `AND`, `OR`, `SWITCH`

#### IF
<img width="573" height="66" alt="image" src="https://github.com/user-attachments/assets/d694df0a-6e66-4f52-9aaf-801dca805318" />

#### IF AND
<img width="883" height="74" alt="image" src="https://github.com/user-attachments/assets/7ebde9f3-ceda-4d10-8fc9-4533ccddb73c" />

#### IF OR
<img width="532" height="152" alt="image" src="https://github.com/user-attachments/assets/6a83755f-ed69-40fb-a9be-80ff94473be9" />


- Text: `CONCATENATE`, `UPPER`, `LEFT`

 <img width="442" height="894" alt="image" src="https://github.com/user-attachments/assets/4aba06f4-46d8-418f-aa8f-5d1cc40a23c7" />


- Date: `YEAR`, `MONTH`, `EOMONTH`

<img width="864" height="839" alt="image" src="https://github.com/user-attachments/assets/88f7213a-987c-440b-b10a-6bc1ac68a089" />

---

## 🕒 Time Intelligence

- `TOTALYTD()`, `SAMEPERIODLASTYEAR()`, `DATESINPERIOD()`  
- Running totals with `CALCULATE()` + `DATESBETWEEN()`

<img width="760" height="504" alt="image" src="https://github.com/user-attachments/assets/c2c475ec-df8b-4cb9-9936-5691d97c30d8" />

---

## 🧩 Joining and Relationships
- Use `RELATED()` to pull related data from dimension tables into calculated columns or measures.

<img width="447" height="55" alt="image" src="https://github.com/user-attachments/assets/dc467ebf-725c-4c4d-a9a5-a43dc5b53d49" />

---

## 📊 Output Requirement
- All calculated results must be displayed in **Matrix visuals only**.  
- Group results by **Region, Month, Product Category, and Customer Segment**.  
- **No other visualizations allowed.**

<img width="944" height="225" alt="image" src="https://github.com/user-attachments/assets/be7300a4-7747-40d5-a82d-fd8211ac5ac4" />

---



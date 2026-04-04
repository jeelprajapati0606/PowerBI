# 📊 Data Leverager – Power Query Transformation Project

## 📌 Project Overview

This project demonstrates a complete data transformation workflow using Power BI (Power Query Editor).
It simulates a real-world data engineering scenario where data is extracted, cleaned, transformed, and combined from multiple sources.

🎯 Objective

To:

Extract data from different sources

Clean and transform data

Combine datasets

Perform analysis-ready transformations

📂 Data Sources Used

🌐 HTML Table (from web)

📁 Excel Files:

Sales_Jan.xlsx

Sales_Feb.xlsx

Sales_Mar.xlsx

👨‍💼 Employee Dataset:

EmployeeID, Name, Department, Region, Join Date

## 🚀 Steps Performed

## 1️⃣ Data Extraction
🔹 Load HTML Table

Steps:

Open Power BI

Go to Home → Get Data → Web

Paste URL (e.g., Wikipedia table)

Select required table → Load


🔹 Load Multiple Excel Files (Folder)

Steps:

Go to Home → Get Data → Folder

Select folder containing all sales files

Click Combine & Transform

Use Append Queries from Folder



🔹 Load Employee Dataset

Steps:

Go to Home → Get Data → Excel

Select employee file

Load data into Power Query


## 2️⃣ Basic Transformations

Steps (Power Query Editor):

Remove blank rows → Home → Remove Rows

Promote headers → Home → Use First Row as Headers

Rename columns → Double-click column name

Change data types → Right-click → Change Type (use Locale if needed)

Remove duplicates → Home → Remove Rows → Remove Duplicates
Filter null values


## 3️⃣ Text Cleaning Tools

Used Functions:

UPPER()

LOWER()

TRIM()

CLEAN()

REPLACE()

Split Column by Delimiter

Steps:

Select column

Go to Transform Tab

Apply required text functions


## 4️⃣ Numeric Transformations

Steps:

Round values → Transform → Round

Create Profit Column:

Profit = Revenue - Cost

Go to:

Add Column → Custom Column


## 5️⃣ Date & Time Transformations

Steps:

Extract Year/Month/Day →

Add Column → Date → Select option

Extract Quarter → same menu

Create Fiscal Month

Calculate Age from Birthdate


## 6️⃣ Conditional Columns & Indexing

🔹 Sales Category

Steps:

Go to Add Column → Conditional Column

Apply conditions:

Condition	   Category

≥ 10000	       High

5000–9999	     Medium

< 5000	       Low

🔹 Index Columns

Add 0-based → Add Column → Index Column → From 0

Add 1-based → From 1


## 7️⃣ Pivoting & Unpivoting

🔹 Pivot

Steps:

Select column

Go to Transform → Pivot Column

🔹 Unpivot

Steps:

Select columns

Go to Transform → Unpivot Columns



## 8️⃣ Merging & Appending

🔹 Merge Queries

Steps:

Go to Home → Merge Queries

Join using:

Region OR

EmployeeID

🔹 Append Queries

Steps:

Go to Home → Append Queries → Append as New

Combine Jan, Feb, Mar data

## 9️⃣ Grouping & Aggregation

Steps:

Go to Transform → Group By

Group by Region

Add:

Total Sales

Average Order Value

Transaction Count

## 🔟 Data Profiling & Quality

Steps:

Enable from:

👉 View Tab

Column Profile

Column Distribution

Column Quality

Used for:

Finding missing values

Detecting errors

Understanding data distribution

# Image Explanation

<img width="1195" height="1315" alt="image" src="https://github.com/user-attachments/assets/bcc91cdd-296a-4d72-8416-36b194164926" />

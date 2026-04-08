# 📊 Data Modeler Project

## Building a Star Schema Data Model in Power BI

### 🎯 Objective

This project is about creating a clean and well-structured data model in Power BI using fact and dimension tables.

It helps to understand:

Table relationships

Primary Key & Foreign Key

Star Schema design

Cardinality (1, M:1)

Inactive relationships

### 📂 Dataset

The project uses the following tables:

#### 🟢 Fact Tables

Sales_Fact → Main sales data

Returns_Fact → Product return data

#### 🔵 Dimension Tables

Customer_Dim

Product_Dim

Region_Dim

Date_Dim

## ⚙️ Step-by-Step Process

### 🔹 Step 1: Load Data

Open Power BI

Click Get Data → Excel

Load all tables

### 🔹 Step 2: Clean Data (Power Query)

Remove blank rows

Set correct data types

Remove duplicates (only in dimension tables)


#### 👉 Important:

Primary keys (like CustomerID, ProductID) should be unique

### 🔹 Step 3: Create Relationships

Go to Model View and connect tables:

Sales_Fact → Customer_Dim

Sales_Fact → Product_Dim

Sales_Fact → Region_Dim

Sales_Fact → Date_Dim

Returns_Fact → Sales_Fact

Returns_Fact → Date_Dim (inactive)

#### 👉 Set:

Cardinality = Many to One

Filter direction = Single

### 🔹 Step 4: Star Schema

Keep Sales_Fact in center

Connect all dimension tables around it

#### 👉 This structure is called Star Schema

### 🔹 Step 5: Handle Returns Table

Keep Returns_Fact as separate table

Use inactive relationship for Return Date

### 🔹 Step 6: Create Hierarchies

Date → Year > Quarter > Month > Date

Region → Country > State > City

Product → Category > Subcategory > Product

### 🔹 Step 7: Format Data

Revenue → Currency

Quantity → Whole Number

Date → Date format

### 🔹 Step 8: Validate Model

Use Matrix Visual to check:

Sales by Category & Region

Revenue by Customer Segment

Returns by Year

### ✅ Final Result

Clean data model

Star schema design

Proper relationships

Ready for reporting

# Project Presentation

<img width="1369" height="1149" alt="image" src="https://github.com/user-attachments/assets/0ba8a5c2-4304-4d2a-9ae9-081251187fb2" />

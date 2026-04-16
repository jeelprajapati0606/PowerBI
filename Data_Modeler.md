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

<img width="1166" height="734" alt="image" src="https://github.com/user-attachments/assets/9e3c8f96-6e80-4164-83fb-ebe4f5e8815d" />


#### 👉 Set:

Cardinality = Many to One

Filter direction = Single

### 🔹 Step 4: Star Schema

Keep Sales_Fact in center

Connect all dimension tables around it

#### 👉 This structure is called Star Schema
<img width="1208" height="924" alt="image" src="https://github.com/user-attachments/assets/b38cf261-9447-4740-a19d-ee263ea6ce9f" />

### 🔹 Step 5: Snowflake Schema

Keep Sales_Fact in center

Connect all dimension tables around it

#### 👉 This structure is called Snowflake Schema
<img width="1130" height="903" alt="image" src="https://github.com/user-attachments/assets/4612f40f-e38a-45f0-b9ff-5262c2be45a4" />


### 🔹 Step 6: Handle Returns Table

Keep Returns_Fact as separate table

Use inactive relationship for Return Date

### 🔹 Step 7: Create Hierarchies

#### Date → Year > Quarter > Month > Date

<img width="333" height="163" alt="image" src="https://github.com/user-attachments/assets/233d7f90-493b-40ca-9118-19f0f6eebffa" />


#### Region → Country > State > City

<img width="323" height="121" alt="image" src="https://github.com/user-attachments/assets/da9f7527-faa7-4743-b494-32114512eabd" />


#### Product → Category > Subcategory > Product

<img width="330" height="116" alt="image" src="https://github.com/user-attachments/assets/4f548936-bca6-451f-8411-b0148e0b4dee" />


### 🔹 Step 8: Format Data

Revenue → Currency

Quantity → Whole Number

Date → Date format

### 🔹 Step 9: Validate Model

Use Matrix Visual to check:

Sales by Category & Region

Revenue by Customer Segment

Returns by Year

### ✅ Final Result

Clean data model

Star schema design

Proper relationships

Ready for reporting



# 🎓 Student Performance Dashboard (Power BI)

## 📌 Overview
This project analyzes **student performance data** by combining exam scores, attendance records, and behavior logs.  
It transforms raw datasets into **interactive insights** using Power BI data modeling, DAX measures, and visual storytelling.

---

## 📂 Datasets
1. **Students.csv** – StudentID, Name, Gender, Class, Section  
2. **Scores.csv** – StudentID, Subject, ExamType, Score, MaxScore, Term  
3. **Attendance.csv** – StudentID, Date, Status (Present/Absent), Reason  
4. **Behavior.csv** – StudentID, Date, BehaviorType, Notes  

---

## 🛠️ Data Preparation
- Load all datasets and create relationships.  
- Clean column names, correct datatypes.  
- Handle nulls/missing values appropriately.  

---

## 🔢 DAX Measures
- **% Score = Score / MaxScore**
  
<img width="621" height="68" alt="image" src="https://github.com/user-attachments/assets/e8a178c9-5a54-4628-9ae4-f4d8bb2b15d5" />
 
- **Average Score per Subject**
 
<img width="423" height="118" alt="image" src="https://github.com/user-attachments/assets/559d12ab-a20b-496b-af66-a8821631ecb5" />

- **Attendance %**
<img width="804" height="168" alt="image" src="https://github.com/user-attachments/assets/e4a9d96f-b3f0-443c-97a0-0ed9e41ca5a3" />

- **Behavior Count per Type**
<img width="716" height="139" alt="image" src="https://github.com/user-attachments/assets/eb0313d2-8c52-4a9f-ac08-93bbdc2d13fc" />

- **Performance Category** (High/Medium/Low using SWITCH/IF)  
<img width="688" height="195" alt="image" src="https://github.com/user-attachments/assets/ec8bc402-6cf2-42b7-9a5d-d644b941c8db" />


---

## 📊 Visualizations
- **Bar Chart:** Average scores by Subject and Class  
- **Line Chart:** Performance trend by Term  
- **Donut Chart:** Behavior type distribution  
- **Table:** Student‑wise scores with conditional formatting  
- **Card KPIs:** Total Students, Average Attendance, Avg Score  

---

## 🎛️ Interactivity
- Slicers for Class, Section, Subject, Term  
- Drillthrough page for individual student profile
  <img width="1124" height="591" alt="image" src="https://github.com/user-attachments/assets/7223572f-c456-42d0-9005-ffae28349235" />
 
- Tooltips with mini charts or metrics  
<img width="795" height="540" alt="image" src="https://github.com/user-attachments/assets/a8cfb84f-96c8-4a5c-804f-54c5cc36caf9" />


---

## 📈 Key Insights
- Highest scoring subject is **Maths**  
- Overall attendance is **above 90%**  
- Majority of students fall in **Low performance category**  
- Most common behavior is **Disruptive**

# Dashboard Visualization

<img width="1219" height="800" alt="image" src="https://github.com/user-attachments/assets/c7645b8c-e0ac-4d7b-a0fc-40b771fd2a1d" />

# 🔗Video Explanation Link

https://drive.google.com/file/d/1tBEknxU2YzioQcZG1QMIvvJyzvT6AqZg/view?usp=sharing

---



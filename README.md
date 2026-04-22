# 🏥 Healthcare Analytics Dashboard | Power BI Project

## 📌 Project Overview  
This project is an interactive **Healthcare Analytics Dashboard** built in Power BI to analyze hospital operations, patient trends, doctor performance, financial metrics, and time-based healthcare insights.

The dashboard transforms raw healthcare data into meaningful insights to support better decision-making in hospital management, cost control, and patient care optimization.

---

## 🎯 Objectives  
- Analyze patient admissions and discharges  
- Evaluate hospital performance  
- Assess doctor efficiency and workload  
- Understand medical condition impact on cost and treatment  
- Study financial performance (billing & insurance)  
- Identify time-based trends in healthcare operations  

---

## 📂 Dataset Information  
The dataset includes hospital-level patient records:

- Patient Name  
- Age & Gender  
- Blood Type  
- Medical Condition  
- Date of Admission  
- Discharge Date  
- Doctor  
- Hospital  
- Insurance Provider  
- Billing Amount  
- Admission Type  
- Test Results  

---

## 🛠 Tools & Technologies  
- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Power Query (Data Cleaning & Transformation)  
- Data Modeling (Star Schema)  
- Date Table with Time Intelligence  

---

## 🔗 Data Model Design  
- Created a dedicated Date Table for time analysis  
- Relationships:
  - Admission Date → Date Table (Active)  
  - Discharge Date → Date Table (Inactive using USERELATIONSHIP)  
- Star schema design for optimized performance  

---

## 📊 Dashboard Pages  

### 🟦 Executive Overview  
- Total Patients, Billing, Avg Stay KPIs  
- Admission trends over time  
- Gender distribution  
- Admission type breakdown  
- Top hospitals overview  

### 🏥 Hospital Performance  
- Hospital-wise patient distribution  
- Total billing by hospital  
- Average length of stay  
- Billing vs patients analysis  
- Hospital ranking  

### 👨‍⚕️ Doctor Performance  
- Patient load per doctor  
- Revenue generated per doctor  
- Average stay per doctor  
- Doctor ranking using RANKX  
- Efficiency vs workload analysis  

### 💰 Financial Analysis  
- Billing by insurance provider  
- Revenue by admission type  
- High-cost patient analysis  
- Billing trends over time  

### ⏱ Time Analysis  
- Admissions vs discharges trend  
- Net patient flow  
- Weekly and monthly patterns  
- Seasonal demand analysis  

---

## 🧠 Key Insights  
- Identified top-performing hospitals based on revenue and efficiency  
- Found doctors with highest workload and contribution  
- Analyzed cost distribution across medical conditions  
- Observed patient admission and discharge trends over time  
- Compared emergency vs elective admission impact  

---

## 📌 Key DAX Measures  
- Total Patients = COUNTROWS()  
- Total Billing = SUM()  
- Average Stay = DATEDIFF()  
- Revenue per Patient = DIVIDE()  
- Ranking using RANKX()  
- Time intelligence using CALENDAR and USERELATIONSHIP  

---

## 🚀 Features  
- Fully interactive dashboard with slicers  
- Cross-page filtering (Hospital, Doctor, Disease, Admission Type)  
- Dynamic time-based analysis  
- Clean KPI design  
- Optimized data model  

---

## 📈 Project Outcome  
This project demonstrates strong skills in:
- Power BI Dashboard Development  
- Data Cleaning & Modeling  
- DAX Calculations  
- Business Intelligence Storytelling  
- Healthcare Data Analysis  

---

## 👨‍💻 Author  
**Muhammad Waqas**  
📧 Email: kbwaqas@gmail.com  
🔗 LinkedIn: www.linkedin.com/in/muhammad-waqas-a7532251  

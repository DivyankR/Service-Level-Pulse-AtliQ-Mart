# 📦 Supply Chain Data Analysis – Power BI | MS Excel

This project is part of the **Codebasics Resume Project Challenge**, where I applied my technical, analytical, and communication skills to analyze supply chain performance and build actionable dashboards.

🔗 [Challenge Link](https://codebasics.io/challenge/codebasics-resume-project-challenge)  
📊 [Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNjZjZGViYTgtYzM3NC00YzI4LTg4NmUtOTRjNzZjYTBmNjk4IiwidCI6IjQxNGIwZDFmLWRjMTMtNDBkNS05ZWU0LTJlYmFiOWZmZDI1OSJ9&pageName=f8a381bac99343ff16ff)

---

## 📝 Problem Statement

**AtliQ Mart**, a fast-growing FMCG company based in Gujarat, India, currently operates in Surat, Ahmedabad, and Vadodara. With plans to expand into Tier-1 cities, the company must resolve a critical service issue: several key customers have not renewed their contracts due to poor delivery performance.

To address this, the management has asked the supply chain analytics team to track key delivery KPIs on a daily basis:

- **On-Time Delivery (OT%)**
- **In-Full Delivery (IF%)**
- **On-Time In-Full Delivery (OTIF%)**

---

## 🎯 Your Role

Imagine yourself as **Peter Pandey**, a newly hired data analyst at AtliQ Mart. Following a stakeholder business review meeting (provided in comic form), you are responsible for:

- ✅ Creating KPIs based on a defined metrics list  
- ✅ Building a dashboard according to stakeholder requirements  
- ✅ Generating additional insights to support better decision-making

---

## 📁 Data Model

<p align="center">
  <img src="https://github.com/DivyankR/Service-Level-Pulse-AtliQ-Mart/blob/master/resources/data%20model.png" width="600">
</p>

---

## 📊 Dashboard Views

### 1. Customer View  
<p align="center">
  <img src="https://github.com/DivyankR/Service-Level-Pulse-AtliQ-Mart/blob/master/resources/customer%20view.png" width="600">
</p>

### 2. Product View  
<p align="center">
  <img src="https://github.com/DivyankR/Service-Level-Pulse-AtliQ-Mart/blob/master/resources/product%20view.png" width="600">
</p>

### 3. Business View  
<p align="center">
  <img src="https://github.com/DivyankR/Service-Level-Pulse-AtliQ-Mart/blob/master/resources/business%20view.png" width="600">
</p>

### 4. Business KPIs  
<p align="center">
  <img src="https://github.com/DivyankR/Service-Level-Pulse-AtliQ-Mart/blob/master/resources/business%20KPIs.png" width="600">
</p>

### 5. Product-wise KPIs  
<p align="center">
  <img src="https://github.com/DivyankR/Service-Level-Pulse-AtliQ-Mart/blob/master/resources/product%20wise%20kpis.png" width="600">
</p>

---

## 📌 Key Insights

- Overall service levels are below target for OT%, IF%, and OTIF%, affecting contract renewals.
- **Coolblue** shows the poorest performance across LIFR% and VOFR%.
- Customers like **Elite Mart**, **Info Stores**, **Sorefoz Mart**, **Acclaimed Stores**, and **Vijay Stores** also have LIFR% below 60%.
- OTIF% is significantly below target for multiple customers, placing them in the **red zone**.
- Of 57,096 total order lines, **16,491 were delayed**, broken down as:
  - 8,255 delayed by 1 day  
  - 5,136 delayed by 2 days  
  - 3,100 delayed by 3 days
- **Vadodara** performs the worst across OTIF%, OT%, and IF% when compared with Ahmedabad and Surat.
- By KPI:
  - Worst OTIF%: *Coolblue*
  - Worst OT%: *Lotus Mart*
  - Worst IF%: *Elite Mart*

---

## 📘 Key Learnings

- Built a **matrix heatmap** for quick issue identification  
- Utilized advanced DAX functions like `ISINSCOPE()`  
- Created custom visuals using **donut charts**, **card visuals**, and **100% stacked bar charts**  
- Gained knowledge of essential supply chain KPIs:
  - **OT** – On-Time Delivery
  - **IF** – In-Full Delivery
  - **OTIF** – On-Time In-Full
  - **LIFR** – Line Item Fill Rate
  - **VOFR** – Volume Fill Rate

---

> ⚙️ Tools Used: **Power BI**, **MS Excel**, **DAX**, **Data Modeling**

---

Feel free to ⭐ this project if you found it helpful or want to bookmark it!

# Supply Chain Data Analysis - Power BI | MS Excel

This project is a part of Codebasics Resume Project Challenge. I have leveraged my technical, analytical and soft skills to conduct this analysis.

Link to the [Challenge](https://codebasics.io/challenge/codebasics-resume-project-challenge)

Link to the [Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNjZjZGViYTgtYzM3NC00YzI4LTg4NmUtOTRjNzZjYTBmNjk4IiwidCI6IjQxNGIwZDFmLWRjMTMtNDBkNS05ZWU0LTJlYmFiOWZmZDI1OSJ9&pageName=f8a381bac99343ff16ff)

## Problem Statement
AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodara. They want to expand to other metros/Tier 1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend their annual contracts due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘On-time delivery (OT) %’, ‘In-full delivery (IF) %’, and OnTime in full (OTIF) %’ of the customer orders daily basis against the target service level set for each customer.

### Task:  

Peter Pandey is the data analyst in the supply chain team who joined AtliQ Mart recently. He has been briefed about the the task in the stakeholder business review meeting. Now imagine yourself as Peter Pandey and play the role of the new data analyst who is excited to build this dashboard and perform the following task:

- Create the metrics according to the metrics list.
- Create a dashboard according to the requirements provided by stakeholders in the business review meeting. You will be provided with the transcript of this business review meeting in comic form.
- Create relevant insights not provided in the metric list/stakeholder meeting.

## Data Model
<p align="center">
    <img src="https://github.com/DivyankR/Service-Level-Pulse-AtliQ-Mart/blob/master/resources/data%20model.png" width="600">
</p>

## Business Dashboard - Customer View
<p align="center">
    <img src="https://github.com/DivyankR/Service-Level-Pulse-AtliQ-Mart/blob/master/resources/customer%20view.png" width="600">
</p>

## Business Dashboard - Product View
<p align="center">
    <img src="https://github.com/DivyankR/Service-Level-Pulse-AtliQ-Mart/blob/master/resources/product%20view.png" width="600">
</p>

## Business Dashboard - Business View
<p align="center">
    <img src="https://github.com/DivyankR/Service-Level-Pulse-AtliQ-Mart/blob/master/resources/business%20view.png" width="600">
</p>

## Business Dashboard - Business KPIs View
<p align="center">
    <img src="https://github.com/DivyankR/Service-Level-Pulse-AtliQ-Mart/blob/master/resources/business%20KPIs.png" width="600">
</p>

## Business Dashboard - Product Wise KPIs View
<p align="center">
    <img src="https://github.com/DivyankR/Service-Level-Pulse-AtliQ-Mart/blob/master/resources/product%20wise%20kpis.png" width="600">
</p>

## Key Insights from the Analysis
- 'On Time Delivery %', 'In Full Delivery %' & 'On Time In Full Delivery %' are important business KPIs and are well below target values and should be improved to bring back the customers who have not renewed annual contracts.
- 'Coolblue' is not served well as it has lowest LIFR% and VOFR%. Other customers like Elite Mart, Info Stores, Sorefoz Mart, Acclaimed Stores and Vijay Stores are also not served well as these all have LIFR% below 60%.
- 'On Time In Full Delivery %' for 'Coolblue', 'Acclaimed Stores', 'Lotus Mart', 'Elite Mart', 'Info Stores', 'Sorefoz Mart' and 'Vijay Stores' are extremely off target (They are in Red-Zone of difference between actual and target values.)
- 'On Time Delivery%' for 'Coolblue', 'Acclaimed Stores' and 'Lotus Mart' are extremely off target (They are in Red-Zone of difference between actual and target values.)
- 'In Full Delivery%' for Elite Mart, Info Stores, Sorefoz Mart and Vijay Stores (They are in Red-Zone of difference between actual and target values.)
- Out of 57096 order lines for various products, 16491 order lines are delivered late with 8255, 5136 and 3100 orders being delayed by 1-day, 2-day and 3-day.
- Vadodara has the worst OTIF%, OT% and IF% out of Ahmedabad, Surat and Vadodara.
-  'Coolblue' has the worst OTIF%, 'Lotus Mart' has the worst OT% and 'Elite Mart' has the worst IF%.

## Key Learnings
- Learnt how to create a heatmap-like visual with matrix.
- Learnt about new DAX functions like ISINSCOPE().
- Leant how to create new KPI visuals using donut visual, card visual and 100% stacked Bar Chart.
- Learnt about Supply Chain concepts like LIFR, VOFR, OTIF, OT and IF.

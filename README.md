# Power-BI Projects

![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=white)

**Project 1: Insurance Premium & Claims Performance Dashboard with KPIs**

## 📌 Business Problem

Insurance companies need visibility into premium collection, policy maturity, claims payout, and ROI performance. 
The objective of this dashboard is to:

- Track premium payments across policy types
- Monitor claim payouts and maturity amounts
- Analyze ROI and payment durations
- Provide regional performance insights

## 📂 Dataset Overview

The dataset includes:

- Insurance Policy Details
- Policy Type
- Agent Information
- Regional & Zonal Managers
- Premium Payment Information
- Claims & Maturity Amount

Note: Synthetic dataset created for analytical demonstration.

## 🧩 Data Model

The model follows a star schema:

- Insurance Policy table (Fact table)
- Agent table (Dimension)
- Policy Type table (Dimension)
- Regional Manager table (Dimension)
- Zonal Manager table (Dimension)

Relationships:
- Policy ID → Fact table key
- Agent ID → Linked to policy table
- Region ID → Linked to regional manager

<img width="1427" height="713" alt="image" src="https://github.com/user-attachments/assets/bcb6b9ce-553d-4e58-ac60-e2fb31752217" />

## 📐 Key DAX Measures

### Total Premium Amount
Total Premium Amount = 
Annual Premium * Premium Payment Duration

### Total Premium Paid
Total Premium Paid =
SUM(Premium Payments[Payment Amount])

### Annualized ROI
Annualized ROI =
(Maturity Amount - Total Premium Paid) / Total Premium Paid

### CAGR
CAGR =
((Maturity Amount / Total Premium Paid)^(1/Years)) - 1

<img width="1132" height="730" alt="image" src="https://github.com/user-attachments/assets/cb30820a-cf25-433f-82b2-0aa8c92dfb74" />


<img width="938" height="671" alt="image" src="https://github.com/user-attachments/assets/9d27cd75-c44b-403e-8aaa-47005545e397" />


<img width="935" height="608" alt="image" src="https://github.com/user-attachments/assets/55b1fb40-5faa-4a83-85e2-6de8aa69c392" />




**Project 2: Blinkit Grocery Sales**

Check out the full project [here](https://app.powerbi.com/reportEmbed?reportId=c0e1ac82-1086-4cc8-bd07-ae85e50febea&autoAuth=true&ctid=65df6988-476e-454d-9c40-393bbe68634a).

![image](https://github.com/user-attachments/assets/eef85043-c434-4189-9eca-41edeada0b8e)


**Project 3: Data Professional Salary**

This is a real time data collected from people through a survey.

Check out the full project [here](https://app.powerbi.com/reportEmbed?reportId=051090b0-e4a0-42a5-b2f7-55a1ddb614c2&autoAuth=true&ctid=65df6988-476e-454d-9c40-393bbe68634a).

![image](https://github.com/user-attachments/assets/dfbd640f-80fd-41eb-84a5-950e96708bdc)


**Project 4: Basic**

Check out the full dashboard [here](https://app.powerbi.com/reportEmbed?reportId=18d956e1-460f-4820-b099-4915b1a64550&autoAuth=true&ctid=65df6988-476e-454d-9c40-393bbe68634a).

![image](https://github.com/user-attachments/assets/a6cd4e02-0d7b-4b8a-9427-8b24509aa513)

# Covid--19-data-analysis
This project is a dashboard representation of the Covid-19 on power bi  for better analysis 
# 🦠 COVID-19 Data Analysis Dashboard

## 📌 Project Title:
**COVID-19 Data Analysis**

## 📖 Problem Statement:
Understanding COVID-19 trends across countries and WHO regions helps in planning informed public health policies, allocating healthcare resources, and identifying high-risk zones.

## 🎯 Objective:
To analyze global COVID-19 data and visualize:
- Overall and country-wise case trends
- Recovery and death rates
- Weekly growth and new case surges
- WHO region-wise comparisons

## 🧾 Dataset Attributes:
The dataset used contains the following columns:

| Column Name               | Description                                     |
|--------------------------|-------------------------------------------------|
| `Country/Region`         | Name of the country or region                   |
| `Confirmed`              | Total confirmed cases                          |
| `Deaths`                 | Total deaths                                   |
| `Recovered`              | Total recoveries                               |
| `Active`                 | Currently active cases                         |
| `New cases`              | New cases reported in the latest update        |
| `New deaths`             | New deaths reported in the latest update       |
| `New recovered`          | New recoveries reported in the latest update   |
| `Deaths / 100 Cases`     | Deaths per 100 confirmed cases (mortality rate)|
| `Recovered / 100 Cases`  | Recoveries per 100 confirmed cases             |
| `Deaths / 100 Recovered` | Deaths per 100 recoveries                      |
| `Confirmed last week`    | Total confirmed cases one week ago             |
| `1 week change`          | Change in cases over one week                  |
| `1 week % increase`      | Weekly case growth rate (%)                    |
| `WHO Region`             | World Health Organization region classification|

![image](https://github.com/user-attachments/assets/cf085908-30f7-486c-bb50-20d5567255b7)

---

## 🛠️ Tools Used:
- **Power BI** – for interactive visualizations and dashboards
- **Python (optional)** – for initial data cleaning or preprocessing
- **CSV dataset** – structured pandemic data

---

## 📊 Visualizations Created in Power BI:
1. **Cards** – Total Confirmed, Deaths, Recovered, and Active
2. **Bar Charts** – Top 10 countries by:
   - Confirmed cases
   - New daily cases
3. **Stacked Area Chart** – Composition of confirmed cases (Active, Recovered, Deaths)
4. **Scatter Plot** – Deaths per 100 cases vs Recovery per 100 cases
5. **Matrix with Conditional Formatting** – Weekly % growth (simulated heatmap)
6. **Stacked Bar Chart** – WHO region-wise summary (Confirmed, Deaths, Recoveries)
7. **Slicers** – Filter dashboard by `Country/Region` or `WHO Region`

![Power BI Desktop 04_07_2025 20_18_53](https://github.com/user-attachments/assets/9db0b80b-2f4e-42a8-b440-6cc9e58bd116)

---

## 📈 Key Insights:
- Countries such as the **USA, India, and Brazil** report the highest confirmed cases.
- **Recovery rates** exceed 85% in many regions, but **death rates vary significantly**.
- **Weekly % increase** highlights ongoing surges in certain regions.
- **Americas and Europe** show highest case burden, while **SE Asia shows better recovery efficiency**.

---

- Data Source: WHO or public COVID-19 APIs/datasets (based on actual data source used)
- Visuals & Dashboard: Created using Power BI Desktop
- python code and liabraries : To visualize the data on numpy , pandas , matplotlib and seaborn  

---

## ✅ Outcome:
A comprehensive visual story that presents the spread, severity, and recovery trends of COVID-19 globally — enabling better public health insights and communication.

---

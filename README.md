## 🌍 CAMPAIGN INSIGHTS AND ANALYTICS DASHBOARD
# 📊 Project Overview
This interactive Power BI dashboard explores customer demographics, spending patterns, and income distribution across different countries and education levels. It helps identify how customer profiles and background factors (like age, education, and marital status) influence total income and purchasing behavior.

#🎯 Objective
To analyze customer data and provide key marketing insights through visual storytelling — enabling better targeting, segmentation, and campaign decisions.

#🧾 Dataset Information
Source: CustomerMarketing.csv Rows: 2,240  Columns: 28

# Key Columns:

Demographics: Year_Birth, Education, Marital_Status, Country

Financial: Income, Total Spending, Average Income

Campaigns: AcceptedCmp1–5, Response, Complain

Purchases: NumWebPurchases, NumStorePurchases, NumCatalogPurchases

# 📐 Dashboard Layout
🧱 Page 1 – Overview
Filters: Marital Status, Country, Education, Year of Birth


Charts & Visuals:

Donut chart: Count of marital_Status by Country

Line chart: Count of Income and Sum of Response by Country

WaterFall chart: Sum of Response by country

🧱 Page 2 – Income Analysis

Funnel: Count of Income by Education

Pie Chart: Count of Income by Marital_Status

Tree Map: Count of Income by Education

Area Chart: Sum of NumWebVisitsMonth by Country

🧮 Key Measures Used
Measure Description Total Customers DISTINCTCOUNT(ID) Total Spendings Sum of all product spending columns Sum of Income SUM(Income) Average Income AVERAGE(Income) Total Purchases Combined total of web, store, and catalog purchases Response Rate DIVIDE(SUM(Response), [Total Customers])

🎨 Design & Theme
Element Style Background Dark Blue Visual Cards Charcoal Gray Accent Colors Orange, Yellow, Green Font Segoe UI (Professional Power BI Default) Visual Type Mix Cards, Donuts, Gauges, Line & Bar Charts

🎨 All visuals and layout were designed by Mahender Reddy

💡 Key Insights
Spain (SP) contributes the highest income share among all countries.

Customers with Graduation and Master’s degrees dominate total income.

Majority of the customer base lies between ages 35–55.

Married customers and mid-aged graduates represent the strongest segment.

🧰 Tools & Technologies
Power BI Desktop – Data modeling and dashboard design

DAX – Measure creation

Excel / CSV – Data cleaning and preprocessing

📸 Dashboard Preview

<img width="1408" height="793" alt="Screenshot 2025-11-05 105706" src="https://github.com/user-attachments/assets/8d920acf-feaf-4cd8-8ac4-d466536c0b9a" />
<img width="1385" height="787" alt="Screenshot 2025-11-05 110038" src="https://github.com/user-attachments/assets/c393d84f-5535-42d6-8c3b-39287b20736f" />
<img width="1426" height="802" alt="Screenshot 2025-11-05 110122" src="https://github.com/user-attachments/assets/7a56ba60-f2ac-44fb-80a3-6ab6555f1273" />
<img width="1384" height="789" alt="Screenshot 2025-11-05 105959" src="https://github.com/user-attachments/assets/3053612b-a7d7-483b-8d97-83e97a476001" />
<img width="1389" height="783" alt="Screenshot 2025-11-05 105843" src="https://github.com/user-attachments/assets/c03494fe-0bfc-431d-90fa-47aa9b7d2037" />



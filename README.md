# 📊 Mobile Sales Performance Dashboard | Power BI

## 📑 Table of Contents
- [Project Overview](#-project-overview)
- [Project Demo](#-project-demo-57-second-presentation)
- [Dataset](#-dataset)
- [Business Problem & Solution](#-business-problem--solution)
- [Key Business Insights](#-key-findings--business-insights)
- [Key Features](#️-key-features)
- [Technologies & Skills](#️-technologies--skills-demonstrated)
- [Development Process (ETL)](#-development-process-etl--visualization)
- [Challenges & Learnings](#-challenges--learnings)
- [How to Run Locally](#️-how-to-run-locally)
- [Conclusion](#-conclusion)
- [Repository Structure](#-repository-structure)
- [Contact](#-lets-connect)
---

## 📌 Project Overview
This project demonstrates the development of an interactive **Mobile Sales Performance Dashboard** using Microsoft Power BI. The dashboard transforms raw sales data into meaningful business insights through dynamic visualizations, KPI tracking, and interactive filtering. 
The primary objective is to empower stakeholders to monitor sales performance, identify trends, evaluate regional performance, and make data-driven business decisions swiftly.

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-005571?style=for-the-badge)
![Data Visualization](https://img.shields.io/badge/Data_Visualization-FF5722?style=for-the-badge)

<p align="center">
  <img src="DASHBOARD IMAGE.png" alt="Dashboard Preview" width="100%">
</p>

## 🎥 Project Demo (57-Second Presentation)
*Watch the brief video presentation below to see the dashboard in action:*

https://github.com/user-attachments/assets/20434a96-1d97-4bdb-9b66-636a9f799895

## 💾 Dataset
The raw data used for this dashboard is available in this repository. 
* **Download the Dataset here:** [Mobile_Sales_Dataset.xlsx](https://github.com/user-attachments/files/30154384/Mobile_Sales_Dataset.xlsx)

  
## 🎯 Business Problem & Solution
* **The Challenge:** Organizations often struggle to analyze large volumes of complex sales data efficiently, leading to delayed decision-making. 
* **The Solution:** This centralized dashboard provides a clear, interactive view of critical sales metrics, enabling users to drill down into daily trends, city-wise performance, and brand analytics instantly without needing technical expertise.

## 💡 Key Findings & Business Insights
- **Overall Performance:** Successfully visualized **₹769M+** in total sales across **4K+** customer transactions, with an Average Order Value (AOV) of **₹40K**.
- **Volume Metrics:** Tracked massive sales volume with over **19K+** units sold over the analyzed period.
- **Brand Dominance:** Apple and Samsung emerged as the top-performing brands in terms of overall revenue generation.
- **Payment Preferences:** UPI and Credit Cards were the most frequently used payment methods among high-value transactions.
- **Regional Trends:** Tier-1 cities demonstrated the highest volume of smartphone purchases, indicating strong urban market penetration.

## ⚙️ Key Features
- **Interactive Monthly Slicer:** Seamless navigation across different time periods for temporal analysis.
- **Dynamic KPI Cards:** Real-time tracking of Total Sales, Quantity, Transactions, and Average Value at a glance.
- **Geospatial Analysis:** Interactive map visual showcasing sales distribution and density by city.
- **Trend Analysis:** Line charts displaying monthly and weekday sales patterns to identify peak sales periods.
- **Categorical Breakdowns:** Detailed, drillable analysis by Mobile Model, Customer Ratings, and Payment Methods.

## 🛠️ Technologies & Skills Demonstrated
* **Tools Used:** Microsoft Power BI, Microsoft Excel
* **Data Engineering:** Power Query (Data Cleaning, Shaping, and Transformation)
* **Data Modeling:** Relational Data Modeling, Star Schema
* **Calculations:** DAX (Data Analysis Expressions)
* **Core Competencies:** Data Visualization, Business Intelligence, Dashboard Development, Analytical Problem Solving, Presentation & Communication Skills.

## 🔄 Development Process (ETL & Visualization)
To build this robust reporting tool, the following end-to-end data process was implemented:
1. **Data Extraction:** Imported the raw dataset (.xlsx) into Power BI Desktop.
2. **Data Transformation (Power Query):** Cleaned the data by removing duplicates, handling missing values, and formatting columns (Date, Currency, Text) to ensure data accuracy.
3. **Data Modeling:** Established active relationships between fact and dimension tables to create an optimized data model (Star Schema).
4. **Calculations (DAX):** Authored custom DAX measures for core business KPIs (e.g., *Total Sales, Total Quantity, Average Sales Value, YoY Growth*).
5. **Data Visualization:** Designed an intuitive and interactive UI with slicers, map visuals, and trend lines, focusing on user experience (UX) and clarity.

## 🧠 Challenges & Learnings
- **Challenge:** Managing complex DAX calculations for dynamic time-intelligence reporting (e.g., Month-over-Month growth).
- **Solution:** Leveraged Power BI's built-in time intelligence functions and created a dedicated Calendar table in the data model to ensure accurate temporal calculations.
- **Learning:** Deepened understanding of Data Modeling (Star Schema) and how proper table relationships drastically improve dashboard performance.
## ⚙️ How to Run Locally
To view or edit this dashboard on your local machine:
1. Download and install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Clone this repository or download the ZIP file.
3. Open the `Dashboard.pbix` file in Power BI Desktop.
4. *(Optional)* If the dataset path breaks, go to `Transform Data` > `Data Source Settings` and point it to the downloaded `Dataset.xlsx` file.

## 🏁 Conclusion
This dashboard provides a holistic, 360-degree view of the mobile sales landscape. By leveraging these interactive insights, sales and marketing leadership can optimize their campaigns, target high-performing regions, and make informed inventory decisions to drive future revenue growth.

## 📂 Repository Structure

```text
📂 mobile-sales-dashboard-powerbi
│
├── 📜 README.md
├── 📊 Dashboard.pbix
├── 🖼️ Dashboard.png
├── 🎥 Mobile_Sales_Performance_Dashboard_Demo.mp4
└── 📗 Dataset.xlsx
```

---

## 🤝 Let's Connect

If you found this project interesting or have any feedback, feel free to reach out!

- 🔗 **LinkedIn:** https://www.linkedin.com/in/shubham-kumar-0b537a364
- 📧 **Email:** shubham9546appu@gmail.com

# 🚦 311 Complaint & Collision Analytics – NYC

This repository contains a data-driven project that explores the relationship between **311 Service Requests** and **Motor Vehicle Collisions** in **New York City**. By analyzing these datasets, we aim to uncover patterns, identify high-risk areas, and provide actionable insights for improving urban service efficiency and public safety.

---

## 📌 Project Goals
- **Analyze the relationship** between 311 service complaints and motor vehicle collisions.
- **Identify patterns and trends** in areas with higher complaint volumes and accident reports.
- **Improve urban service delivery** through data-driven recommendations.

---

## 🏗️ Data Architecture
We designed a scalable data pipeline leveraging:
- **Medallion Architecture** (Bronze-Silver-Gold) for clean separation of data stages:
  - **Bronze Layer**: Raw data ingestion.
  - **Silver Layer**: Cleaned and standardized data with fact and dimension tables.
  - **Gold Layer**: Aggregated data optimized for analysis and reporting.
- **Star Schema Design** for easy querying and reporting.

### **Key Datasets**
- 311 Service Requests (from 2010 to present)
- Motor Vehicle Collision Data (updated weekly)
- NYC Precinct Data (for location mapping)
- NYC Household Income Data (by ZIP code)

---

## 🔧 Tools & Technologies
- **Python** for data extraction and processing (pagination handling for API limits)
- **Google BigQuery** and **Google Cloud Storage** for data warehousing and staging
- **Power BI** for dashboard creation and visualization
- **NYC Open Data APIs** as data sources

---

## 📈 Key Performance Indicators (KPIs)
- Total complaints and action rates (by borough, precinct, income level)
- Average response time and resolution success rates
- Trends in complaint types, collision types, and contributing factors
- Collision trends over time and injury/fatality rates
- Vehicle complaints and collision frequencies by location and precinct

---

## 📊 Interactive Dashboard
Access the live **Power BI** report to explore key insights interactively:
[Power BI Dashboard](https://app.powerbi.com/links/JctFGH20p7?ctid=6f60f0b3-5f06-4e09-9715-989dba8cc7d8&pbi_source=linkShare&bookmarkGuid=da4b9e99-6ed3-4768-9f80-2b31b28c3c87)

---

## 🌟 Team Members
- Victor Louie  
- Powell Ahaneku  
- Inna Nykolaichuk  
- Elizabeth Treimanis  
- Kossi Gamli

---

## 🚀 Future Enhancements
- Integration of real-time data feeds for continuous updates.
- Geospatial analysis of complaint-to-precinct distances using mapping tools.
- Enhanced drill-through features in dashboards to explore specific cases.

---

## 📚 References
- [NYC Open Data – 311 Service Requests](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/about_data)
- [NYC Open Data – Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data)
- [NYPD Precinct Data](https://wgetsnaps.github.io/nyc.gov--nypd-videos/html/nypd/html/home/precincts.shtml)
- [NYC Household Income Data](https://data.cccnewyork.org/data/map/66/median-incomes)

---

Thank you for visiting! If you have any feedback or ideas for improvement, feel free to open an issue or reach out to us. 🚀

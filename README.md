
# Project Title




# Inventory & Product Demand Analysis Dashboard

### Dashboard Link :  
👉 **Interactive Dashboard on Power BI Service:**  
https://app.powerbi.com/links/MXkiJ-1tes?ctid=5dc72bfc-5d6a-43a1-b24f-aaaf7dae1d47&pbi_source=linkShare


## Problem Statement

This dashboard helps businesses understand **product demand and inventory availability** more effectively. It enables decision-makers to identify products with high demand but limited availability, analyze inventory gaps, and assess the potential revenue impact due to stock shortages.

By using this dashboard, operations and supply chain teams can improve **inventory planning, stock replenishment, and demand forecasting**, ultimately reducing stock-outs and improving customer satisfaction.

---

## Steps Followed

* **Step 1:** Raw data was collected and stored in structured tables related to products, inventory, and demand.
* **Step 2:** Data cleaning and preprocessing were performed using **SQL**, including filtering, selecting relevant columns, and joining multiple tables.
* **Step 3:** A **LEFT JOIN** was used to merge product master data with demand and availability data to ensure no product records were lost.
* **Step 4:** The cleaned dataset was imported into **Power BI Desktop**.
* **Step 5:** Data modeling was performed to establish proper relationships between tables.
* **Step 6:** Necessary measures and calculated fields were created to analyze demand, availability, and revenue impact.
* **Step 7:** Interactive visuals such as bar charts, cards, and tables were added to represent product-wise demand and availability.
* **Step 8:** Slicers were added to enable dynamic filtering based on products and dates.
* **Step 9:** Dashboard layout and theme were finalized to improve readability and business presentation.
* **Step 10:** The report was published to **Power BI Service** for online access and sharing.

---

## Data Cleaning Using SQL

SQL was used to prepare the data before loading it into Power BI. The key operations included:

* Database creation and selection
* Checking for distinct order dates
* Joining product and inventory tables
* Selecting required fields such as Product ID, Demand, Availability, and Unit Price
* Removing unnecessary columns to improve data quality

This ensured the dataset was **clean, consistent, and analysis-ready**.

---

## Dashboard Features

* Product-wise demand analysis
* Availability vs demand comparison
* Identification of inventory gaps
* Revenue impact analysis using unit price
* Interactive filters and slicers for better insights

---
<img width="1601" height="805" alt="Image" src="https://github.com/user-attachments/assets/0c6fb649-9373-4e9c-b820-c8d763a5289e" />
<img width="1601" height="802" alt="Image" src="https://github.com/user-attachments/assets/2a38ffe5-8136-4501-9469-22e5913f51ae" />


---

## Insights

Following insights can be drawn from the dashboard:

### [1] Demand vs Availability

* Certain products show **high demand but limited availability**, indicating potential stock-out risks.
* Products with balanced demand and availability perform more consistently.

### [2] Revenue Impact

* Products with high unit price and high demand contribute significantly to potential revenue.
* Inventory shortages in such products can directly impact sales performance.

### [3] Inventory Planning

* The dashboard highlights products that require **urgent replenishment**.
* Helps prioritize inventory decisions based on demand patterns.

---

## Business Applications

* Inventory management and stock optimization
* Retail and FMCG demand analysis
* Supply chain and operations decision-making
* Procurement and replenishment planning

---

## Tools & Technologies Used

* **Power BI** – Dashboard creation and visualization
* **SQL** – Data cleaning, joins, and preprocessing
* **Excel / CSV** – Source dataset

---

## Learnings

* Practical implementation of SQL for real-world data cleaning
* Power BI data modeling and interactive dashboard design
* Converting raw data into meaningful business insights
* Understanding demand–inventory relationships in operations

---

⭐ If you found this project useful, consider giving the repository a star!

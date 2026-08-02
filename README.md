# 🌾 3MTT Capstone Project: Nigeria Agricultural Output Analysis (DA-11)

An interactive Excel dashboard and data pipeline analyzing crop production, harvested area, and productivity yield across Nigeria's 36 states and Federal Capital Territory (FCT).

---

## 📌 Project Overview
- **Author:** KOLEOSO ADEOLA
-  Fellow ID:FE/23/70197965
- **Program:** 3MTT Nigeria (Data Analysis Track)
- **Dataset Source:** National Bureau of Statistics (NBS) NASS Report (2022/2023)
- **Target Crops:** Rice, Yam, Cassava
- **Primary Tooling:** Microsoft Excel (Power Query, Pivot Tables, Advanced Formulas, Dashboard Design)

---

## 🎯 Objectives
1. **Data Cleaning & ETL:** Ingest raw NASS survey data, remove double-counting risks, standardize data types, and eliminate missing value flags.
2. **Aggregated Modeling:** Summarize production volumes, total planted/cultivated area, and crop yields across all 6 geopolitical zones.
3. **Interactive Visual Dashboard:** Build an executive-level 16:9 widescreen dashboard with zone-level slicers for rapid policy and performance filtering.
4. **Strategic Insights:** Formulate tailored regional policy and supply chain recommendations for top and bottom-performing states.

---

## 📂 Repository Structure


---

## 🛠️ Data Pipeline & Transformation Log (ETL)

All data transformation steps were documented in the **`Data_Log`** sheet:

| Step | Action Taken | Purpose / Reason |
| :--- | :--- | :--- |
| **1** | Imported raw NASS dataset into Power Query | Established reliable connection to source data |
| **2** | Filtered scope to Rice, Yam, and Cassava | Focused project scope on required staple crops |
| **3** | Removed top metadata headers | Standardized table structure for tabular parsing |
| **4** | Filtered out Zone summary rows | Prevented double-counting of regional metrics |
| **5** | Replaced `(S)` and `-` flags with `0` | Resolved numerical data type conflicts |
| **6** | Standardized schema `[Crop] [Metric]` | Eliminated duplicate column header errors |
| **7** | Calculated `Sub-total Planted Area` (Column S) | Enabled dynamic total cultivated area KPI metrics |

---

## 📊 Key Findings & Strategic Insights

### **National Summary**
- **Total Crop Output:** ~53.47 Million Tons
- **Total Cultivated Area:** ~18.11 Million Hectares
- **Top Producing State:** Benue State (~9.37M Tons)
- **Dominant Crop:** Cassava accounts for the largest overall production volume, followed closely by Yam and Rice.

### **Regional Strategic Highlights**
* **North Central (Breadbasket):** High output driven by massive Yam production. *Recommendation:* Prioritize cold-chain logistics and processing hubs in Benue & Niger to minimize post-harvest loss.
* **North West & North East:** Massive potential for Rice cultivation expansion. *Recommendation:* Expand high-yield seed distribution and solar-powered irrigation infrastructure.
* **Southern Zones (South West / South South):** Major producers of Cassava. *Recommendation:* Establish cassava starch and flour agro-processing clusters near primary farming communities.

---

## 💻 How to Use the Excel Workbook
1. Clone or download this repository.
2. Open `3MTT Project Capstone final.xlsx` in Microsoft Excel 2016 or newer.
3. Navigate to the **`Dashboard`** tab.
4. Click on any geopolitical zone on the **Top Slicer Bar** to dynamically filter all KPIs, bar charts, doughnut charts, and state performance metrics.

---

## 👥 Connect & Feedback
If you have any feedback or questions regarding this project, feel free to reach out via [koleoso-adeola(
https://www.linkedin.com/in/koleoso-adeola-32762388?

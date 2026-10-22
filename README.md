# 🌍 Global Country Development & Economic Comparison Analytics

A multi-page Power BI business intelligence solution providing a multidimensional comparative analysis of ~263 global countries and territories across economics, healthcare, energy resources, and infrastructure.

---

## 📊 Project Overview
This project integrates complex global datasets into an interactive, 5-page dashboard ecosystem. It empowers stakeholders to evaluate national economic outputs, demographic indicators, energy production/export balances, and global digital/transport connectivity.

---

## 🚀 Key Dashboard Pillars & Dynamic KPIs

### 1. 📈 Executive Overview
- **Global Indicators:** Aggregates **7.0 Billion** total population and an average global GDP of **$255.85B**.
- **Economic Output Leaders:** Tracks top economies led by the **United States ($11.75T)** and **China ($7.26T)**.
- **Development Insights:** Regional comparisons across Higher, Middle, and Lower income brackets.

### 2. 🏥 Health & Social Indicators
- **Demographics:** Tracks average global life expectancy (**57.91 years**), average birth rate (**18.95**), and average infant mortality (**30.25** per 1,000 live births).
- **Longevity Top Performers:** Highlights top nations in life expectancy including **Andorra (83.51)**, **Macau (82.03)**, and **San Marino (81.62)**.

### 3. 💵 Economic Performance
- **Macroeconomic Metrics:** Tracks average GDP growth (**3.85%**), average inflation (**4.48%**), and total global exports (**10T**).
- **Growth Momentum & Risks:** Identifies high-growth expansion leaders (**Iraq at 52.3%**, **Chad at 38.0%**) alongside contraction and high-inflation risk zones.

### 4. ⚡ Energy & Natural Resources
- **Resource Production:** Measures total oil production (**78.66M bbl/day**), total gas production (**2.88T cu m**), and total electricity generation (**18.85T kWh**).
- **Export Powerhouses:** Highlights key energy exporters including **Saudi Arabia (7.9M bbl/day)** for oil and **Russia (0.17T cu m)** for natural gas.

### 5. 🌐 Infrastructure & Connectivity
- **Digital Reach:** Tracks **908M** internet users and **193M** internet hosts worldwide.
- **Logistics Backbone:** Maps **33M km** of highways and **1M km** of active railway networks.

---

## 📈 Dashboard & Architecture Preview

### 1. Executive Overview Dashboard
![Executive Overview Dashboard](Images/Page%201.png)

### 2. Health & Education Analysis
![Health & Education Analysis](Images/Page%202.png)

### 3. Economic Performance Analysis
![Economic Performance Analysis](Images/Page%203.png)

### 4. Global Energy & Natural Resources
![Energy Analysis](Images/Page%204.png)

### 5. Infrastructure Analysis
![Infrastructure Analysis](Images/Page%205.png)

---

## 🛠️ Data Modeling & Technical Architecture

* **Data Cleaning & ETL (Power Query):** Systematically handled null value imputations across numerical indicators, created custom region lookup mapping, and standardized metadata types across ~263 territories.
* **Schema Design (Galaxy Schema):** Built a multi-fact Constellation Schema connecting 4 distinct Fact tables (`Fact Demographic Health`, `Fact Economic Metrics`, `Fact Energy Resources`, `Fact Infrastructure`) to a central shared conformed dimension (`Dim Country`).
* **DAX Analytics:** Authored 26 custom DAX measures for dynamic cross-filtering, regional aggregations, and comparative metrics evaluation.
* **UI/UX Design:** High-contrast dark theme with consistent side navigation menus and custom conditional formatting tables.

---

## 💡 Strategic Takeaways
- **Income Level Drive:** GDP per capita strongly correlates with life expectancy, internet penetration, and lower infant mortality rates globally.
- **Energy Security Split:** Strategic bargaining power is concentrated among key net energy exporters (Saudi Arabia, Russia, Canada, Algeria, Norway).
- **Growth vs. Stability:** Fast-growing economies are frequently volatile or recovering resource-dependent markets, whereas high-income giants display steady 0–5% annual growth.

# ✈️ Flights Analysis Dashboard  
A Power BI Project for Aviation Data Analytics

## 📌 Project Overview
This project presents a fully interactive **Power BI dashboard system** built to analyze real-world U.S. aviation data.  
The goal is to transform raw flight records into clear visual insights that support operational decisions, performance evaluation, and delay management across airlines and airports.

The analysis uses **1.9M+ U.S. domestic flight records (Kaggle dataset)** from 2008.

This project includes **three dashboards**, each answering key business questions about airline performance, airport operations, and delays.

---

## 📊 Dashboard Pages

### **1️⃣ Flights Overview Dashboard**
A high-level summary of overall flight activity — including total flights, cancellations, delays, monthly trends, and top airports and airlines.  
Designed to help identify seasonal patterns and understand general performance.

### **2️⃣ Airports & Airplanes Analysis**
Focuses on airport operations and aircraft performance — highlighting busiest airports, rush hours, and airplanes with the longest distances and durations.  
Useful for infrastructure planning and fleet optimization.

### **3️⃣ Delay Analysis Dashboard**
Analyzes when, where, and why delays occur.  
Shows peak delay periods(by hour, day, month), delay causes, airport-level delay behavior, and airline-specific performance to support operational improvements.

---

## 🛠️ Tools & Technologies Used
- **Power BI Desktop**  
- **Power Query** (data cleaning & transformation)  
- **DAX** (measures, KPIs, advanced calculations)  
- **Data Modeling** using Star Schema methodology  
- **Figma** (UI/UX dashboard planning & layout design)  
- Interactive visuals, drill-throughs, and advanced tooltips  

---

## 📦 Dataset Details
- **Source:** Kaggle — U.S. Domestic Flights (2008)  
- **Records:** ~1.9M  
- **Fields Included:** Airlines, airports, schedules, distances, delays, aircraft details, and flight status  

### 🔧 Data Preparation Included
- Handling missing or inconsistent values  
- Cleaning airline and airport fields  
- Creating date/time hierarchies  
- Structuring delay causes  
- Building optimized star-schema tables  

---

## 🏗️ Data Model Description
The data model follows a **Star Schema**, containing:

- **Fact Table:**  
  - Flights Fact (distances, delays, statuses, times, IDs)

- **Dimension Tables:**  
  - Date
  - Time
  - Airline  
  - Airport   

This structure ensures fast performance and clean relationships (one-to-many).

---

## ▶️ How to Use
1. Download the `.pbix` file from this repository.  
2. Open the file using **Power BI Desktop (latest version recommended).**  
3. Use slicers, filters, and tooltips for interactive exploration.  
4. Switch across the three pages to analyze performance, airport activity, and delay patterns.

---

## 📈 Example Insights
- Delays spike during specific months, days, and hours.  
- Certain airlines show consistently higher average delay durations.  
- Weather-related delays significantly increase during winter.  
- A small group of airports handles a large share of national traffic.  
- Long-distance flights often experience fewer short operational delays.

---



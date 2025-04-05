# 📊 Industrial OEE Monitoring Dashboard – Power BI

Welcome to my **OEE (Overall Equipment Effectiveness)** Monitoring Dashboard built using **Power BI**. This end-to-end project demonstrates my capabilities as a **Data Analyst**, showcasing expertise in data modeling, DAX calculations, interactive dashboard design, production monitoring, and downtime analytics using real-world industrial data.

---

## 🧑‍💼 About Me

As a data analyst passionate about industrial operations, I specialize in transforming raw manufacturing data into actionable insights. In this project, I simulate a real-time production environment to monitor the efficiency of multiple devices over time. My focus is on deriving **meaningful patterns**, **minimizing downtime**, and **enhancing operational efficiency**.

---

## 🧩 Project Overview

This Power BI dashboard is structured across **three key pages**, each offering deep insights into manufacturing performance:

1. **Overall Report**  
2. **Gantt Chart (Timeline Monitoring)**  
3. **Individual Device Analytics**

---

## 🔍 1. Overall OEE Report

### 📌 Purpose:
Provides a **holistic summary of production effectiveness** over time with metrics aligned to industry standards.

### 📊 KPIs Tracked:
| Metric        | Description |
|---------------|-------------|
| **OEE**       | Overall Equipment Effectiveness (Availability × Performance × Quality) |
| **Availability** | How often equipment is available for production |
| **Performance**  | Speed at which equipment runs compared to its optimal |
| **Quality**      | Percentage of defect-free products produced |

#### ✅ Highlights:
- High-level OEE Score: `53.52%`
- Performance: `94.72%`
- Quality: `99.40%`
- Availability: `56.84%`

### 📈 Visuals:
- **OEE Trend Over Time**: Line chart showing OEE trends across selected dates
- **OEE by Device ID**: Horizontal bar chart comparing device efficiency
- **Device Cards**: Each device has detailed stats (OEE, Availability, Performance, Quality)

### 🔧 Filters:
- Interactive **date range slicer**
- **Timeline sliders** for granular selection

---

## ⏱️ 2. Gantt Chart – Device Timeline Monitoring

### 📌 Purpose:
To **monitor device states hourly** and identify periods of productivity, downtime, and disconnection.

### 📊 Status Categories:
- 🟢 **Production**
- 🔴 **Downtime**
- ⚫ **Disconnected**

### 📈 Visuals:
- **Gantt Chart** by Device ID and Date
- Tracks status blocks across hours (00:00 to 08:00 AM and beyond)
- Timeline-based visual storytelling for easy downtime tracking

### 🔧 Filters:
- **Date Range Selector**
- **Hour of the Day** Slicer
- **Device ID & Status** Dropdown

### ✅ Analyst Skill Highlights:
- Custom Gantt visual integration
- Real-time status pattern tracking
- Interactive temporal slicing

---

## 🧠 3. Individual Device Report

### 📌 Purpose:
To provide **deep-dive insights into a selected device**, tracking its performance breakdown and root causes of inefficiency.

### 📊 Key Metrics:
- **Availability**: `54.13%`
- **Performance**: `95.58%`
- **Quality**: `99.94%`
- **Planned Runtime**: `82 days`
- **Actual Runtime**: `44 days`

### 📈 Visuals:
- **Bar Charts** for:
  - Planned vs Actual Runtime
  - Planned vs Actual Quantity
  - Accepted vs Rejected Quality
- **Donut Chart** for Stoppage Breakdown
- **Top 3 Downtime Reasons** table:
  - Operator Inefficiency – 4642 events
  - Not Mentioned – 1988 events
  - Raw Material Shortage – 1221 events

### 🛠️ Tools Used:
- **Calculated Columns & Measures** (DAX)
- **Conditional Formatting** in visuals
- **Drill-through Navigation**
- Custom date-time handling for runtime aggregation

---

## 🚀 Skills Demonstrated

| Skill Area | Demonstration |
|------------|----------------|
| **Power BI** | Multi-page interactive dashboard, filters, bookmarks |
| **Data Modeling** | Normalized device logs, status mappings, date table relationships |
| **DAX** | Custom measures for OEE, Availability, runtime calculations, KPI indicators |
| **Industrial Analytics** | Gantt chart integration, OEE best practices, root cause breakdown |
| **Data Visualization** | Intuitive layout with aligned KPIs, performance diagnostics |
| **Storytelling** | Clear segmentation of dashboard into overview, monitoring, and root cause |
| **Problem Solving** | Timeline reconstruction from log data, status classification logic |

---

## 📌 Use Case Scenarios

✅ Factory production line managers  
✅ Maintenance teams for downtime reduction  
✅ Operations analysts seeking root cause trends  
✅ Manufacturing consultants needing snapshot metrics  

---

## 🛠️ Tech Stack

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query (ETL)**
- **Gantt Custom Visual**
- Excel/CSV as base source (can be replaced with SQL or API feeds)

---

## 📤 Future Enhancements

- Real-time streaming of device data using Power BI service
- Predictive downtime alerts using ML integration
- Maintenance scheduling recommendations
- Exportable automated reports (PDF/email scheduler)

---

## 📎 Screenshots

| Page | Preview |
|------|---------|
| **Overall OEE Report** | ![OEE Overview](![Screenshot 2025-04-02 154430](https://github.com/user-attachments/assets/84f141ef-1b19-4a84-a62d-8cd73d964cc6)) |
| **Device Timeline Gantt** | ![Gantt Chart](![Screenshot 2025-04-02 154500](https://github.com/user-attachments/assets/ab9c35ce-cb8c-4563-8d19-806805e30e42)
) |
| **Individual Device Analysis** | ![Device Report](![Screenshot 2025-04-02 154524](https://github.com/user-attachments/assets/5b5044f4-0a8b-4fe5-a2e5-fee72596e49a)
) |

---

##  Let's Connect

If you liked this project or want to collaborate on analytics/BI projects:

📧 Email: gaderohan2509@gmail.com  
🔗 LinkedIn: [Your LinkedIn](https://www.linkedin.com/in/rohan-gade-299533251)  
📂 Portfolio: [Your Portfolio Website](https://rohangade.carrd.co/)

---

> _"Data is only as valuable as the story it tells. This project turns machine-level data into decisions that matter."_  
> — *Rohan*, Data Analyst

# 📊 HR Dashboard - Power BI Analytics Project

 

## 📚 Table of Contents

- [🧠 Project Overview](#-project-overview)  

- [🎯 Key Metrics & KPIs](#-key-metrics--kpis)  

- [📈 Dashboard Features](#-dashboard-features)  

  - [🔹 Workforce Trends Analysis](#-workforce-trends-analysis)  

  - [🔹 Demographic Insights](#-demographic-insights)  

  - [🔹 Educational Background](#-educational-background)  

  - [🔹 Departmental Analysis](#-departmental-analysis)  

  - [🔹 Position & Location Insights](#-position--location-insights)  

- [🔧 Technical Details](#-technical-details)  

  - [🔗 Data Sources](#-data-sources)  

  - [🧱 Data Model](#-data-model)  

- [🧩 How to Use This Dashboard](#-how-to-use-this-dashboard)  

- [🚨 Key Insights & Recommendations](#-key-insights--recommendations)  

- [📁 Project Structure](#-project-structure)  

- [🚀 Project Development](#-project-development)  

- [🌟 Future Enhancements](#-future-enhancements)  

 

## 🧠 Project Overview  

This Power BI dashboard delivers comprehensive insights into key Human Resources metrics and trends within the organization. It empowers HR professionals and leadership teams to make **data-driven decisions** about recruitment, employee engagement, and workforce planning.

 

---

 

## 🎯 Key Metrics & KPIs

 

- **Active Employees:** 3,409  

- **New Joiners:** 0 *(monitoring period specific)*  

- **Employee Exits:** 5  

- **Attrition Rate:** 14.66% ⚠️ *(requires attention)*  

- **Average Salary:** $79.61K  

- **Average Employee Age:** 41.09 years  

 

---

 

## 📈 Dashboard Features

 

### 🔹 Workforce Trends Analysis

- **Active Employees by Year and Month**  

  Line chart showing steady growth from 2020–2022, peaking at 3,409 employees  

  *(Highlights seasonal hiring patterns and overall expansion)*

 

### 🔹 Demographic Insights

 

**Gender Distribution**

- Female: 39.1%  

- Male: 60.9%  

 

**Age Group Breakdown**

- 36–45: 42.1% *(largest segment)*  

- 26–35: 41.1%  

- 46–55: 6.0%  

- 18–25: 6.0%  

- 55+: 4.8%  

 

### 🔹 Educational Background

- Bachelor's Degree: 2.7K  

- Master's Degree: 0.5K  

- Associate's Degree: 0.1K  

- Other educational levels included

 

### 🔹 Departmental Analysis

- Software: 660 employees  

- Sales: 510  

- Marketing: 334  

- HR: 333  

- Operations: 324  

- Finance: 303  

 

### 🔹 Position & Location Insights

- Role hierarchy: From **Individual Contributors** to **CEO**  

- Work arrangement: **On-site vs. Remote**  

- Management levels breakdown  

 

---

 

## 🔧 Technical Details

 

### 🔗 Data Sources

- Employee master data  

- Demographic & education details  

- Department and position hierarchies  

- Compensation data  

- Calendar & date dimensions  

- Manager reporting lines  

- Termination tracking  

- Marital status info  

 

### 🧱 Data Model

 

**Fact Tables**

- `people_fact`

 

**Dimension Tables**

- `demographic_dim`  

- `department_dim`  

- `education_dim`  

- `job_level_dim`  

- `location_dim`  

- `manager_dim`  

- `marital_dim`  

- `term_dim`  

- `calendar`

 

---

 

## 🧩 How to Use This Dashboard

 

### For HR Professionals:

- Track and reduce **attrition** (currently 14.66%)  

- Monitor **recruitment activity** (no new joiners detected)  

- Analyze **departmental resource allocation**  

- Use **age demographic data** for succession planning  

 

### For Leadership:

- Inform **workforce and strategic planning**  

- Guide **budget allocations** using salary insights  

- Support **diversity goals** through gender and education data  

- Assess **departmental performance**

 

---

 

## 🚨 Key Insights & Recommendations

 

### 🔍 Immediate Attention:

- **High Attrition Rate (14.66%)**  

  Investigate root causes and improve retention strategies  

- **Zero New Joiners**  

  Re-evaluate recruitment channels and employer branding  

- **Succession Planning Need**  

  83% of employees are aged between 26–45

 

### ✅ Positive Trends:

- **Consistent Workforce Growth** (2020–2022)  

- **Well-Educated Staff** with majority holding at least a Bachelor's degree  

 

---

 

## 📁 Project Structure

 

####   HR-Dashboard-Project/

##### ├── HR_Dashboard.pbix # Main Power BI dashboard file

##### ├── README.md # Project documentation

##### ├── data/ # Data sources folder

##### │ ├── employee_data.xlsx # HR data source

##### │ └── department_lookup.csv # Reference data

##### └── screenshots/ # Dashboard visuals

##### └── dashboard_overview.png # Dashboard preview image




---

 

## 🚀 Project Development

 

- **Tool Used:** Power BI Desktop  

- **Dataset:** Sample HR data *(anonymized/synthetic)*  

- **Development Time:** Personal project  

 

---

 

## 🌟 Future Enhancements

 

### 📌 Planned Improvements

- Predictive analytics for attrition  

- Include employee satisfaction & engagement data  

- Drill-through pages for deep-dive insights  

- Geographical visualization based on office locations  

- Mobile-optimized dashboard views  

 

### 💡 Feature Ideas

- Correlate **performance ratings** with tenure and roles  

- Deep-dive **compensation analysis** by department  

- Visualize **recruitment funnel & conversion rates**  

- **Track employee lifecycle** from onboarding to exit

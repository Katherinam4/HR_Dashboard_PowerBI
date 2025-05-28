HR Dashboard - Power BI Analytics Project
📊 Project Overview
This Power BI dashboard provides comprehensive insights into our organization's human resources metrics and trends. It's designed to help HR professionals and leadership make data-driven decisions about workforce management, recruitment, and employee engagement.
🎯 Key Metrics & KPIs
The dashboard tracks several critical HR indicators:

Active Employees: 3,409 total workforce
New Joiners: Currently 0 (monitoring period specific)
Employee Exits: 5 departures tracked
Attrition Rate: 14.66% - requires attention and analysis
Average Salary: $79.61K across all positions
Average Employee Age: 41.09 years

📈 Dashboard Features
1. Workforce Trends Analysis

Active Employees by Year and Month: Line chart showing growth from 2020-2022, reaching peak of 3,409 employees
Tracks seasonal hiring patterns and workforce expansion

2. Demographic Insights

Gender Distribution:

Female: 39.1%
Male: 60.9%


Age Group Breakdown:

36-45: 42.1% (largest segment)
26-35: 41.1%
46-55: 6.0%
18-25: 6.0%
55+: 4.8%



3. Educational Background

Bachelor's degree holders: 2.7K (majority)
Master's degree: 0.5K
Associate's degree: 0.1K
Other education levels tracked

4. Departmental Analysis

Software: 660 employees (largest department)
Sales: 510 employees
Marketing: 334 employees
HR: 333 employees
Operations: 324 employees
Finance: 303 employees

5. Position & Location Insights

Position hierarchy from Individual Contributors to CEO
Location split between On-site and Remote work arrangements
Percentage distribution across management levels

🔧 Technical Details
Data Sources
The dashboard connects to multiple data sources including:

Employee master data
Demographic information
Department and position hierarchies
Salary and compensation data
Calendar/date dimensions
Manager hierarchies
Marital status information
Termination tracking

Data Model Structure

Fact Tables: people_fact
Dimension Tables:

demographic_dim
department_dim
education_dim
job_level_dim
location_dim
manager_dim
marital_dim
term_dim
Calendar



📋 How to Use This Dashboard
For HR Professionals:

Monitor attrition trends - The 14.66% rate needs investigation
Track recruitment success - Zero new joiners may indicate hiring challenges
Analyze departmental distribution for resource planning
Review age demographics for succession planning

For Leadership:

Workforce planning - Use trend data for strategic decisions
Budget planning - Average salary data for compensation planning
Diversity tracking - Gender and education distribution insights
Department performance - Employee distribution across functions

🚨 Key Insights & Recommendations
Immediate Attention Required:

High Attrition Rate (14.66%): Investigate causes and implement retention strategies
Zero New Joiners: Review recruitment processes and market positioning
Age Distribution: 83% of workforce is in 26-45 age range - plan for future succession

Positive Indicators:

Steady Growth: Consistent workforce expansion from 2020-2022
Educational Level: Strong educational background with majority holding bachelor's degrees

📁 File Structure
HR-Dashboard-Project/
├── HR_Dashboard.pbix          # Main Power BI file
├── README.md                  # This documentation
├── data/
│   ├── employee_data.xlsx     # Source data files
│   └── department_lookup.csv  # Reference tables
└── screenshots/
    └── dashboard_overview.png # Dashboard preview

🔄 Project Development

Tools Used: Power BI Desktop
Data Source: Sample HR dataset (likely anonymized/synthetic data for learning purposes)
Development Time: Personal project timeline


🚀 Future Enhancements
Potential Improvements:

Add predictive analytics for attrition forecasting
Include employee satisfaction metrics
Implement drill-through pages for detailed analysis
Add geographical analysis if location data is available
Create mobile-optimized views



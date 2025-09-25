# HR Analytics Dashboard (Tableau)
A comprehensive HR analytics dashboard built in **Tableau** that examines hiring trends, workforce demographics, and compensation analysis across U.S. states and regions, with **New York serving as the headquarters**.

https://github.com/user-attachments/assets/644cc5b0-d2b7-4d45-b772-ca3a20203c0a

https://public.tableau.com/views/HrDashboard_17582195336550/HRSummary?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


---

## 🗺️ Project Overview

This project delivers a comprehensive HR analytics solution that transforms raw HR data into strategic insights. The dashboard enables HR stakeholders to examine:

- **Regional hiring distribution** across U.S. states with New York as headquarters
- **Demographics and diversity patterns** including gender and education breakdowns  
- **Compensation analysis** across different segments and roles
- **Employee tenure and retention** metrics
- **Role-specific insights** including average age and salary by position

The dashboard serves HR leadership, talent acquisition teams, diversity & inclusion initiatives, and compensation planning efforts.

---

## 🎯 Key Goals & Use Cases

### Strategic Objectives
- **Geographic Analysis**: Understand which states/regions contribute most hires, with focus on New York operations
- **Diversity Insights**: Reveal gender and educational attainment patterns across workforce
- **Compensation Equity**: Compare salaries across demographics, education levels, and positions
- **Role Analytics**: Analyze which positions attract older/younger talent and compensation trends
- **Retention Analysis**: Examine employee tenure patterns and identify attrition risks

### Target Users
- HR Leadership & Executives
- Talent Acquisition Teams
- Diversity & Inclusion Officers
- Compensation & Benefits Analysts
- Regional HR Managers

---

## 🧩 Dashboard Structure & Components

| Section | Description | Key Features |
|---------|-------------|--------------|
| **HR Summary** | High-level KPIs and overview metrics | Total employees, avg salary, gender split, tenure overview |
| **Geographic Hiring** | State and regional hiring distribution | Interactive map, bar charts, regional filters |
| **Demographics & Education** | Workforce composition analysis | Gender distribution, education levels, cross-filtering |
| **Compensation Analysis** | Salary comparisons and equity insights | Pay by education, gender, state, role comparisons |
| **Role/Position Insights** | Job-specific metrics and trends | Headcount by role, avg age/salary, position analytics |
| **Tenure Analysis** | Employee retention and term patterns | Tenure distribution, retention trends, turnover insights |

### Interactive Features
**Filters & Controls:**
- State/Region selector
- Gender filter
- Education level filter
- Position/Role filter
- Time period controls

**Advanced Interactions:**
- Cross-filtering between visualizations
- Drill-down capabilities
- Hover tooltips with detailed metrics
- Dynamic parameter controls

---

## 🛠️ Technical Implementation

### Tools & Technologies
- **Primary Platform**: Tableau Desktop/Tableau Public
- **Data Processing**: Excel/CSV data preparation
- **Visualization**: Interactive charts, maps, and dashboards
- **Deployment**: Tableau Public cloud hosting

### Data Requirements
The dashboard utilizes HR data with these key fields:
```
- EmployeeID (unique identifier)
- State/Region (geographic data)
- Gender (demographic data)
- EducationLevel (qualification data)
- Position/JobTitle (role information)
- Age (demographic data)
- Salary (compensation data)
- TermYears/Tenure (retention data)
- HireDate (temporal data)
```

### Data Quality Standards
- Consistent formatting across all fields
- Normalized state/region naming conventions
- Standardized education level categories
- Clean salary data without outliers
- Validated tenure calculations

---

## 📊 Key Performance Indicators (KPIs)

### Primary Metrics
- **Total Workforce Count**: Current employee headcount
- **Geographic Distribution**: Hiring concentration by state
- **Gender Diversity Ratio**: Male/female workforce composition
- **Average Compensation**: Mean salary across segments
- **Average Tenure**: Employee retention duration
- **Education Mix**: Workforce qualification distribution

### Calculated Fields
- Retention rate by department/location
- Compensation equity ratios
- Hiring velocity trends
- Tenure risk indicators

---

## 📈 Sample Insights & Analytics

### Geographic Patterns
- **New York Leadership**: As headquarters, NY shows highest hiring volume and concentration
- **Regional Distribution**: Clear patterns in hiring across different U.S. regions
- **State-level Variations**: Compensation and demographics vary significantly by location

### Demographic Analysis  
- **Gender Representation**: Visibility into workforce gender balance
- **Education Impact**: Higher education levels correlate with compensation differences
- **Age Demographics**: Role-specific age patterns reveal recruitment and succession trends

### Compensation Insights
- **Pay Equity Analysis**: Gender and education-based salary comparisons
- **Geographic Premium**: Location-based compensation adjustments
- **Role-based Variance**: Position-level salary benchmarking

### Retention Patterns
- **Tenure Clusters**: Identification of high-retention vs. high-turnover segments
- **Risk Indicators**: Early warning signals for potential attrition
- **Success Factors**: Characteristics of long-tenured employees

---

## 🚀 Getting Started

### For Viewers
1. Click the live dashboard link above
2. Allow the dashboard to load completely
3. Start with the HR Summary for overview
4. Use filters to drill down into specific segments
5. Navigate between tabs for detailed analysis
6. Hover over charts for additional details

### For Developers
1. Clone this repository
2. Ensure data files are in `/data` directory
3. Open the Tableau workbook (.twb/.twbx)
4. Refresh data connections as needed
5. Test all filters and interactions
6. Publish to Tableau Public/Server

---

## 🔧 Future Enhancements

### Planned Features
- **Predictive Analytics**: Attrition risk modeling and salary forecasting
- **Time Series Analysis**: Historical trends and seasonal hiring patterns
- **Performance Integration**: Link HR metrics with performance data
- **Real-time Updates**: Automated data refresh capabilities
- **Mobile Optimization**: Responsive design for mobile devices

### Advanced Analytics
- Machine learning integration for predictive insights
- Statistical significance testing for compensation equity
- Cohort analysis for retention patterns
- Sentiment analysis integration

---

## 📸 Visual Previews

*video of key dashboard sections would be placed here to showcase the interface and visualizations*


*Dashboard Version: 1.0*  
*Last Updated: December 2024*  
*Built with Tableau Public*

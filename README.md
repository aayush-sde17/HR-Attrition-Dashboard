# 💼 InsightForce: Global HR Attrition Analysis Dashboard

![HR Analytics](https://img.shields.io/badge/HR%20Analytics-Power%20BI-blue?style=for-the-badge&logo=powerbi)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📌 Project Overview

**InsightForce** is a dynamic and interactive data visualization dashboard developed to analyze employee attrition trends across departments, job roles, and demographics. This comprehensive Power BI solution enables HR teams, decision-makers, and business analysts to understand the key factors driving employee attrition and make informed interventions to enhance employee retention strategies.

### 🎯 Objective
To provide actionable insights into employee attrition patterns, identify high-risk departments and employee segments, and enable data-driven workforce management decisions.

---

## 📊 Problem Statement

Organizations face significant challenges in understanding why employees leave and how to reduce attrition rates. Traditional static reports lack interactivity and fail to provide the deep insights needed for effective retention strategies. This dashboard solves these challenges by:

✅ Visualizing attrition patterns across multiple dimensions  
✅ Identifying at-risk employee segments  
✅ Correlating job satisfaction, work-life balance, and compensation with attrition  
✅ Enabling drill-through analysis for individual employee journeys  
✅ Supporting data-driven HR decision-making  

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **BI Tool** | Power BI Desktop |
| **Data Processing** | Power Query |
| **Analytics** | DAX (Data Analysis Expressions) |
| **Data Modeling** | Star Schema / Dimensional Model |
| **Dashboard Type** | Interactive Multi-page Dashboard |

---

## 📂 Dataset Information

### Data Source
**IBM HR Analytics Employee Attrition & Performance Dataset**  
- **Platform**: Kaggle (Public Dataset)
- **Records**: 1,470 employee records
- **Features**: 35+ attributes
- **Format**: CSV

### Key Attributes

#### Employee Demographics
- `EmployeeID`: Unique identifier for each employee
- `Age`: Employee age in years
- `Gender`: Male / Female
- `MaritalStatus`: Single / Married / Divorced
- `Department`: Sales, Research & Development, Human Resources
- `JobRole`: Various roles within departments
- `Education`: Education level (High School, Bachelor, Master, Doctorate)
- `EducationField`: Field of education

#### Employment Details
- `YearsAtCompany`: Tenure at organization (in years)
- `YearsInCurrentRole`: Time in current role (in years)
- `YearsWithCurrManager`: Time under current manager (in years)
- `JobLevel`: 1-5 (hierarchical level)
- `Attrition`: Yes / No (Target Variable)

#### Compensation & Performance
- `MonthlyIncome`: Monthly salary
- `HourlyRate`: Hourly wage
- `PercentSalaryHike`: Percentage increase in salary
- `PerformanceRating`: 1-4 scale

#### Work Environment & Satisfaction
- `OverTime`: Yes / No
- `WorkLifeBalance`: 1-4 scale
- `JobSatisfaction`: 1-4 scale
- `EnvironmentSatisfaction`: 1-4 scale
- `JobInvolvement`: 1-4 scale
- `RelationshipSatisfaction`: 1-4 scale

---

## 🎨 Dashboard Features & Components

### 1. **Overview Dashboard**
Main landing page with key metrics:

| Metric | Description |
|--------|-------------|
| **Total Employees** | Count of all employees in dataset |
| **Attrition Rate (%)** | Percentage of employees who left |
| **Active Employees** | Count of current employees |
| **Avg Monthly Income** | Average salary across organization |
| **Avg Years at Company** | Average tenure |

### 2. 📈 **Attrition by Department**
- Stacked bar chart showing attrition counts and rates
- Department-wise comparison (Sales, R&D, HR)
- Identify which departments have highest turnover

### 3. 👤 **Attrition by Job Role**
- Breakdown of attrition across various job roles
- Roles at highest risk identified
- Performance vs. attrition correlation

### 4. 🎓 **Attrition by Education Level**
- Analysis by education (High School, Bachelor, Master, Doctorate)
- Education field impact on retention
- Skill-level based insights

### 5. 🔢 **Demographic Analysis**
- **Age Group Distribution**: 
  - 18-25, 26-35, 36-45, 46-55, 55+
  - Young talent retention challenges
  
- **Gender Analysis**:
  - Attrition comparison between male and female employees
  - Gender diversity metrics
  
- **Marital Status Impact**:
  - Single, Married, Divorced employee retention

### 6. 💰 **Compensation & Income Analysis**
- Salary distribution of attrited vs. retained employees
- Income vs. attrition correlation
- Identify if low compensation drives attrition
- Salary hike effectiveness

### 7. 😊 **Satisfaction Metrics Dashboard**
- **Job Satisfaction** (1-4 scale):
  - Low satisfaction = High attrition risk
  
- **Work-Life Balance** (1-4 scale):
  - Impact on retention
  
- **Environment Satisfaction**:
  - Workplace conditions correlation
  
- **Job Involvement** (1-4 scale):
  - Engagement vs. attrition

### 8. ⏰ **Tenure & Promotion Analysis**
- Years at company distribution
- Years in current role impact
- Promotion frequency vs. attrition
- Time with current manager relationship

### 9. 🔍 **Drill-Through Views**
- Click on any data point to see individual employee details
- Employee journey analysis:
  - Career progression
  - Satisfaction trends
  - Performance ratings
  - Compensation history

### 10. 📌 **Dynamic Slicers & Filters**
- **OverTime**: Filter by overtime status
- **Department**: Multi-select department filter
- **Job Role**: Role-based filtering
- **Education**: Education level filter
- **Work-Life Balance**: Satisfaction level filter
- **Performance Rating**: 1-4 scale filter
- **Age Range**: Interactive age slider

---

## 📊 Key Insights & KPIs

### Primary Metrics
```
Attrition Rate (%) = (Number of Employees Left / Total Employees) × 100

At-Risk Employees = Employees with Low Satisfaction + High OverTime

Retention Index = 100 - Attrition Rate
```

### Secondary Metrics
- **Department Attrition Rate**: Attrition % per department
- **Role-Based Attrition**: % attrition by job role
- **Age-Based Attrition**: Attrition trends across age groups
- **Satisfaction Impact**: Correlation between satisfaction scores and attrition
- **Income Analysis**: Avg income of attrited vs. retained employees
- **Tenure Risk**: Attrition rate by years at company

---

## 🎯 Feature Highlights

### ✨ Interactive Elements
- 🖱️ **Dynamic Slicers**: Real-time filtering across multiple dimensions
- 🔗 **Cross-filtering**: Selecting one visual updates all related visuals
- 📍 **Drill-through**: Deep dive into employee-level details
- 📈 **Conditional Formatting**: Color-coded risk indicators
- 📊 **Trend Analysis**: Historical attrition patterns

### 🎨 Visualizations Used
- **Card Visuals**: KPI display (Attrition Rate, Avg Income)
- **Column Charts**: Department & Role-wise attrition
- **Pie Charts**: Distribution analysis
- **Line Charts**: Attrition trends over time
- **Scatter Plots**: Correlation analysis (Salary vs. Attrition)
- **Heat Maps**: Multi-dimensional analysis
- **Tables**: Detailed employee records with drill-through
- **Gauges**: Satisfaction level indicators

---

## 🚀 How to Use the Dashboard

### Step 1: Open the Dashboard
1. Download the `.pbix` file from the repository
2. Open in Power BI Desktop (or Power BI Service if published)

### Step 2: Explore Key Metrics
- Review the Overview page for high-level attrition statistics
- Note the overall attrition rate and at-risk employee count

### Step 3: Use Slicers to Filter Data
1. Select a specific **Department** to see department-specific insights
2. Filter by **Job Role** to identify role-based attrition patterns
3. Use **OverTime** slicer to compare full-time vs. overtime employees
4. Adjust **Age Range** to analyze generational trends
5. Select **Work-Life Balance** to correlate with attrition

### Step 4: Analyze Department Performance
- Compare attrition rates across Sales, R&D, and HR
- Identify high-risk departments
- Drill into specific departments for details

### Step 5: Examine Job Roles
- Click on job roles with highest attrition
- Review compensation and satisfaction metrics
- Identify role-specific challenges

### Step 6: Satisfaction & Engagement
- Check job satisfaction vs. attrition correlation
- Analyze work-life balance impact
- Review environment satisfaction scores

### Step 7: Drill-Through Analysis
1. Click on an employee segment in any visual
2. View individual employee details page
3. Review their career progression, salary, and satisfaction history
4. Identify patterns in their profile

### Step 8: Generate Insights
- Document findings for HR team
- Identify trends and patterns
- Prepare retention strategies based on insights

---

## 💡 Key Insights & Recommendations

### Potential Findings
- **Young Talent Attrition**: Employees aged 18-35 show higher attrition
  - *Action*: Develop career growth pathways and mentorship programs
  
- **Overtime Impact**: High overtime correlates with 40% higher attrition
  - *Action*: Implement workload management and flexible working hours
  
- **Satisfaction Gap**: Low work-life balance (score 1-2) = 60% attrition rate
  - *Action*: Improve workplace environment and wellness programs
  
- **Compensation Issue**: 25% lower average salary for attrited employees
  - *Action*: Review compensation benchmarks and salary competitiveness
  
- **Department Hotspot**: Sales department shows 20% higher attrition
  - *Action*: Investigate sales culture and support systems
  
- **New Employee Churn**: 40% attrition within first 2 years
  - *Action*: Strengthen onboarding and first-year engagement programs

---

## 📈 Expected Outcomes

This dashboard enables:
1. ✅ **Proactive Retention**: Identify at-risk employees before they leave
2. ✅ **Data-Driven Decisions**: Make HR decisions backed by data
3. ✅ **Cost Savings**: Reduce expensive replacement & training costs
4. ✅ **Improved Culture**: Address root causes of attrition
5. ✅ **Strategic Planning**: Build workforce development strategies
6. ✅ **Performance Monitoring**: Track retention improvements over time

---

## 📁 Project Structure

```
HR-Attrition-Analysis/
│
├── 📄 README.md                    # Project documentation
├── 📊 InsightForce_Dashboard.pbix  # Power BI Dashboard file
├── 📋 Data/
│   ├── HR-Employee-Attrition.csv   # Raw dataset
│   └── Data_Dictionary.xlsx        # Column descriptions
├── 📑 Documentation/
│   ├── Dashboard_Guide.pdf         # User guide
│   ├── DAX_Formulas.txt            # Custom measures used
│   └── Insights_Report.pdf         # Key findings
└── 🔗 Links/
    └── Kaggle_Dataset_Link.txt     # Dataset source
```

---

## 🔧 Technical Implementation

### Data Model
```
Employee (Main Table)
├── Attributes: Demographics, Employment, Compensation
├── Relationships: N/A (Single fact table design)
└── Primary Key: EmployeeID
```

### DAX Formulas (Sample)

#### Attrition Rate
```dax
AttritionRate = 
DIVIDE(
    CALCULATE(COUNTROWS(Employee), Employee[Attrition]="Yes"),
    COUNTROWS(Employee),
    0
) * 100
```

#### Average Monthly Income (Attrited)
```dax
AvgIncome_Attrited = 
CALCULATE(
    AVERAGE(Employee[MonthlyIncome]),
    Employee[Attrition]="Yes"
)
```

#### At-Risk Employees
```dax
AtRiskCount = 
CALCULATE(
    COUNTROWS(Employee),
    Employee[WorkLifeBalance] <= 2,
    Employee[OverTime]="Yes",
    Employee[Attrition]="No"
)
```

#### Retention Rate
```dax
RetentionRate = 
DIVIDE(
    CALCULATE(COUNTROWS(Employee), Employee[Attrition]="No"),
    COUNTROWS(Employee),
    0
) * 100
```

### Power Query Transformations
- Data type validation
- Handling missing values
- Creating age groups from continuous age
- Categorizing satisfaction levels
- Creating calculated columns for tenure buckets

---

## 📊 Dataset Statistics

| Metric | Value |
|--------|-------|
| **Total Employees** | 1,470 |
| **Attrited Employees** | 237 |
| **Attrition Rate** | 16.1% |
| **Avg Monthly Income** | $6,502 |
| **Avg Tenure** | 7.0 years |
| **Departments** | 3 (Sales, R&D, HR) |
| **Unique Job Roles** | 9 |
| **Age Range** | 18-65 years |

---

## 🎓 Learning Outcomes

Working with this project, you'll gain proficiency in:

- ✅ **Power BI Dashboard Development**: Creating multi-page interactive dashboards
- ✅ **DAX Programming**: Writing complex measures and calculated columns
- ✅ **Data Modeling**: Structuring data for analytical queries
- ✅ **Power Query**: ETL and data transformation
- ✅ **Visualization Design**: Best practices in data visualization
- ✅ **Business Analytics**: Turning data into actionable insights
- ✅ **HR Metrics**: Understanding HR KPIs and metrics
- ✅ **Interactive Design**: Creating user-friendly drill-through experiences

---

## 🔗 Resources & Links

### Dataset Source
- **Kaggle**: [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-employee-attrition-performance)

### Documentation
- [Power BI Official Documentation](https://docs.microsoft.com/en-us/power-bi/)
- [DAX Function Reference](https://dax.guide/)
- [Power Query M Language](https://docs.microsoft.com/en-us/powerquery-m/)

### Tools Required
- Power BI Desktop (Latest version)
- Excel or CSV reader
- GitHub (for version control)

---

## 💼 Business Impact

### HR Team Benefits
- **Time Saving**: Automated insights eliminate manual reporting
- **Actionable Intelligence**: Clear recommendations for retention strategies
- **Risk Identification**: Proactively identify high-risk employees
- **Benchmarking**: Compare departments and roles

### Executive Benefits
- **Strategic Decisions**: Data-backed workforce planning
- **Cost Reduction**: Lower recruitment and training costs
- **Performance Metrics**: Track improvement in retention rates
- **Competitive Advantage**: Build stronger, more stable teams

### Employee Benefits
- **Better Culture**: Insights lead to improved workplace environment
- **Career Growth**: Identify development opportunities
- **Work-Life Balance**: Improvements based on data analysis
- **Fair Compensation**: Salary adjustments based on analysis

---

## 📞 Support & Contribution

### Getting Help
- Review the Dashboard Guide for usage instructions
- Check the DAX Formulas documentation for custom measures
- Refer to the Data Dictionary for column meanings

### Contributing
Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request with detailed description

---

## 📜 License

This project is licensed under the **MIT License** - see LICENSE file for details.

---

## 👨‍💼 Author & Credits

**Created by**: Aayush Gautam  
**Role**: Data Analyst  
**Date**: 2026  

**Dataset Credits**: IBM HR Analytics Dataset (Kaggle)  
**Power BI Community**: For templates and best practices

---

## 🌟 Key Takeaways

> *"Data-driven HR decisions lead to better employee retention, reduced costs, and stronger organizational culture."*

This dashboard transforms raw HR data into actionable insights, enabling:
- 🎯 Proactive attrition management
- 💡 Evidence-based decision making
- 📈 Measurable improvement in retention rates
- 🚀 Strategic workforce planning

---

## 📝 Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | May 2026 | Initial release with core dashboards |
| 1.1 | May 2026 | Added drill-through employee details |
| 1.2 | May 2026 | Enhanced DAX measures and visualizations |

---

## 🎉 Thank You!

Thank you for exploring the InsightForce HR Attrition Analysis Dashboard. We hope this tool helps you make data-driven decisions to improve employee retention and create a better workplace culture.

For questions, suggestions, or collaboration opportunities, feel free to reach out!

**Happy Analyzing! 📊✨**

---

<div align="center">

**⭐ If you found this helpful, please consider starring the repository! ⭐**

[![GitHub Stars](https://img.shields.io/github/stars/aayush-sde17/HR-Attrition-Analysis?style=social)](https://github.com/aayush-sde17/HR-Attrition-Analysis)

</div>

# 👨‍💼 HR Analytics – Employee Attrition Prediction

<div align="center">

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![HR Analytics](https://img.shields.io/badge/HR_Analytics-FF6B6B?style=for-the-badge&logo=microsoft&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-4285F4?style=for-the-badge&logo=google-analytics&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)

*An Excel-powered analytics dashboard identifying key drivers of employee attrition and providing actionable retention strategies*

[Portfolio](https://decodedbyfarhan.tech) • [LinkedIn](https://www.linkedin.com/in/farhan16/) • [GitHub](https://github.com/farhann-16)

</div>

---

## 🎯 Project Objective

Analyze HR employee data using Microsoft Excel to uncover patterns and factors contributing to employee attrition. This project delivers data-driven insights to help HR teams develop targeted retention strategies and reduce turnover costs.

### 💡 Business Impact
- Identify high-risk employee segments
- Quantify impact of overtime on retention
- Provide actionable recommendations for HR policies
- Support data-driven workforce planning

---

## 📁 Dataset Overview

### Data Source
- **Origin:** Kaggle – HR Employee Attrition Dataset
- **Size:** ~1,500 employee records
- **Type:** Real-world anonymized HR data
- **Target Variable:** Attrition (Yes/No)

### Dataset Features

| Category | Features | Description |
|----------|----------|-------------|
| 📊 **Demographics** | Age, Gender, Marital Status | Employee personal information |
| 💼 **Job Details** | Department, Job Role, Job Level | Position and organizational structure |
| 💰 **Compensation** | Monthly Income, Salary Hike % | Earnings and growth metrics |
| ⏰ **Work Patterns** | OverTime, Years at Company, Tenure | Work habits and loyalty indicators |
| 😊 **Satisfaction** | Job Satisfaction, Environment Satisfaction | Employee sentiment scores |
| 🎯 **Performance** | Performance Rating, Promotions | Career progression metrics |
| ✅ **Target** | Attrition | Employee stayed or left (Yes/No) |

### Key Columns

```
📋 Core Attributes:
├── Age                    → Employee age
├── Department             → Sales, R&D, HR
├── JobRole                → Manager, Developer, Analyst, etc.
├── Gender                 → Male/Female
├── MonthlyIncome          → Salary amount
├── YearsAtCompany         → Tenure duration
├── OverTime               → Yes/No
├── JobSatisfaction        → Rating 1-4
└── Attrition              → Yes/No (Target)
```

### Project Files

```
📂 HR-Attrition-Analysis/
├── 📄 HR_Attrition_Data.xlsx
│   └── Raw HR dataset with 1,500+ records
├── 📊 HR_Attrition_Interactive_Dashboard.xlsx
│   ├── Cleaned Data
│   ├── Analysis Sheets
│   ├── Pivot Tables
│   └── Interactive Dashboard
└── 📖 README.md
    └── Project documentation
```

---

## 🧰 Tools & Excel Features Used

### Data Preparation & Cleaning
- ✨ **Remove Duplicates** – Ensuring data quality
- 🔍 **Find & Replace** – Standardizing values
- ✅ **Data Validation** – Input constraints
- 🔧 **Text-to-Columns** – Parsing complex fields
- 🧹 **Handling Missing Values** – Imputation strategies

### Advanced Excel Formulas

```excel
STATISTICAL FUNCTIONS
├── AVERAGE          → Mean calculations
├── STDEV            → Standard deviation
├── CORREL           → Correlation analysis
└── MEDIAN           → Central tendency

LOGICAL FORMULAS
├── IF               → Conditional logic
├── COUNTIFS         → Multi-criteria counting
├── SUMIFS           → Conditional summation
├── AND/OR           → Complex conditions
└── IFERROR          → Error handling

TEXT & DATE FUNCTIONS
├── TEXT             → Date formatting
├── CONCATENATE      → String joining
├── LEN/TRIM         → Text cleaning
└── YEAR/MONTH       → Date extraction
```

### Analysis & Visualization Tools
- 📊 **Pivot Tables** – Dynamic data summarization
- 📈 **Pivot Charts** – Visual representation
  - Column Charts (Attrition by Department)
  - Pie Charts (Gender distribution)
  - Histograms (Age distribution)
  - Scatter Plots (Income vs Satisfaction)
- 🎨 **Conditional Formatting** – Visual highlights
  - Data bars for quick comparison
  - Color scales for correlation matrices
  - Icon sets for KPI indicators
- 🎚️ **Slicers** – Interactive filtering
- 🔄 **Timelines** – Date-based analysis

### Dashboard Design
- Interactive KPI cards
- Multi-dimensional filtering
- Dynamic chart updates
- User-friendly navigation
- Professional color scheme

---

## 🔍 Key Analyses Performed

<div align="center">

| Analysis Type | Focus Area | Business Question |
|---------------|------------|-------------------|
| 📊 **Departmental Analysis** | Attrition by Department | Which departments lose most employees? |
| 👔 **Role-Based Analysis** | Attrition by Job Role | Which positions have highest turnover? |
| ⏰ **Overtime Impact** | Work-Life Balance | How does overtime affect retention? |
| 💰 **Compensation Study** | Salary vs Attrition | Does higher pay reduce attrition? |
| ⏳ **Tenure Analysis** | Years at Company | When are employees most likely to leave? |
| 😊 **Satisfaction Correlation** | Job Satisfaction | Link between happiness and retention? |
| 👥 **Demographic Patterns** | Age & Gender | Which demographics are at risk? |
| 📈 **Performance Analysis** | Ratings vs Attrition | Do high performers stay longer? |

</div>

---

## 📈 Dashboard Insights & Key Findings

### 💼 Key Performance Indicators

<table>
<tr>
<td align="center" width="33%">
<h3>💼 Overall Attrition</h3>
<h1>23.2%</h1>
<p><em>237 out of 1,470 employees left</em></p>
</td>
<td align="center" width="33%">
<h3>⏱️ Avg Tenure (Left)</h3>
<h1>6.6 years</h1>
<p><em>Employees who left the company</em></p>
</td>
<td align="center" width="33%">
<h3>⏱️ Avg Tenure (Stayed)</h3>
<h1>7.0 years</h1>
<p><em>Employees who remained</em></p>
</td>
</tr>
<tr>
<td align="center" width="33%">
<h3>💰 Avg Income (Left)</h3>
<h1>$5,620</h1>
<p><em>Monthly income of departed employees</em></p>
</td>
<td align="center" width="33%">
<h3>💰 Avg Income (Stayed)</h3>
<h1>$5,747</h1>
<p><em>Monthly income of retained employees</em></p>
</td>
<td align="center" width="33%">
<h3>⏰ Overtime Attrition</h3>
<h1>36.6%</h1>
<p><em>Attrition rate for OT employees</em></p>
</td>
</tr>
</table>

### 🔸 Critical Findings

#### 1️⃣ **Overtime Crisis**
> Employees working **overtime** are **60% more likely** to leave compared to regular-hours employees

```
Overtime: YES  →  Attrition: 36.6%
Overtime: NO   →  Attrition: 22.9%
────────────────────────────────
Impact: +13.7 percentage points
```

#### 2️⃣ **Departmental Disparities**
| Department | Attrition Rate | Risk Level |
|------------|----------------|------------|
| 📊 **Sales** | 28.4% | 🔴 High |
| 🔬 **R&D** | 21.8% | 🟡 Medium |
| 👥 **HR** | 19.2% | 🟢 Low |

**Sales department** shows critical attrition levels, requiring immediate intervention.

#### 3️⃣ **Income Gap Analysis**
- Employees who **left** earned **$127 less** per month on average
- Income disparity suggests compensation plays a role
- However, overtime impact exceeds salary influence

#### 4️⃣ **Tenure Sweet Spot**
```
Peak Attrition Periods:
├── 0-2 years    → 28.5% (Onboarding phase)
├── 5-7 years    → 25.3% (Mid-career plateau)
└── 10+ years    → 15.2% (Stabilized workforce)
```

#### 5️⃣ **Satisfaction Correlation**
- **Strong negative correlation** (-0.68) between job satisfaction and attrition
- Employees with satisfaction score < 2 have **3x higher** attrition risk
- Environment satisfaction equally critical

---

## 💡 Strategic Recommendations

### 🎯 Immediate Actions (0-3 Months)

#### 1. **Overtime Management**
```
✅ Implement mandatory overtime limits
✅ Provide overtime compensation bonuses
✅ Hire additional staff in high-OT departments
✅ Monitor weekly hours with alerts
```

#### 2. **Sales Department Intervention**
```
✅ Conduct exit interviews with sales staff
✅ Review sales quota structures
✅ Improve commission structures
✅ Enhance career progression paths
```

#### 3. **Compensation Review**
```
✅ Benchmark salaries against industry standards
✅ Provide retention bonuses for high-risk roles
✅ Implement transparent salary bands
✅ Review and adjust underperforming roles
```

### 🚀 Medium-Term Strategies (3-12 Months)

#### 4. **Retention Programs**
- 🎓 **Mentorship Programs** – Pair new hires with veterans
- 📚 **Skill Development** – Invest in training and certifications
- 🎯 **Career Pathing** – Clear advancement opportunities
- 🏆 **Recognition Systems** – Employee appreciation programs

#### 5. **Work-Life Balance**
- 🏠 **Flexible Work Options** – Remote/hybrid models
- ⏰ **Flexible Hours** – Core hours with flexibility
- 🌴 **Enhanced PTO** – Competitive vacation policies
- 🧘 **Wellness Programs** – Mental health support

#### 6. **Engagement Initiatives**
- 📊 **Regular Pulse Surveys** – Monthly satisfaction checks
- 💬 **Open Communication** – Town halls and feedback sessions
- 🎉 **Team Building** – Regular social events
- 🎁 **Perks & Benefits** – Enhanced employee benefits

---

## 📊 Dashboard Preview

### Main Components

```
┌─────────────────────────────────────────────────────────┐
│  🎯 KPI SUMMARY CARDS                                   │
│  Attrition Rate | Avg Tenure | Income Comparison        │
├─────────────────────────────────────────────────────────┤
│  📊 ATTRITION BY DEPARTMENT (Column Chart)              │
│  Sales, R&D, HR comparison with trend lines             │
├─────────────────────────────────────────────────────────┤
│  ⏰ OVERTIME IMPACT ANALYSIS (Pie Chart)                │
│  Attrition split: Overtime vs Regular hours             │
├─────────────────────────────────────────────────────────┤
│  💰 INCOME DISTRIBUTION (Histogram)                     │
│  Salary ranges vs attrition correlation                 │
├─────────────────────────────────────────────────────────┤
│  ⏳ TENURE VS ATTRITION (Scatter Plot)                  │
│  Years at company correlation analysis                  │
├─────────────────────────────────────────────────────────┤
│  🎚️ INTERACTIVE FILTERS                                │
│  Gender | Department | Job Role | Age Group             │
└─────────────────────────────────────────────────────────┘
```

---

## 🚀 How to Use This Dashboard

### Step 1: Download the File
```bash
# Clone the repository
git clone https://github.com/farhann-16/Data_Science.git
cd Data_Science/Excel_2

# Or download directly
# HR_Attrition_Interactive_Dashboard.xlsx
```

### Step 2: Open in Excel
1. Open `HR_Attrition_Interactive_Dashboard.xlsx` in Microsoft Excel
2. Enable editing if prompted
3. Ensure macros are enabled for full functionality

### Step 3: Explore the Dashboard
- 🎚️ **Use Slicers** to filter by:
  - Gender (Male/Female)
  - Department (Sales/R&D/HR)
  - Job Role (Manager/Developer/Analyst)
  - Age Group (20-30/30-40/40-50/50+)
- 📊 **View Dynamic Charts** that update with filters
- 💡 **Review KPIs** for quick insights
- 📈 **Analyze Trends** across dimensions

### Step 4: Customize Analysis
1. Navigate to the **Analysis** sheet
2. Modify pivot tables for deeper insights
3. Add new charts or metrics
4. Refresh all data to see updates

---

## 🎓 Learning Outcomes

### Skills Developed

<table>
<tr>
<td width="50%">

**Technical Skills**
- ✅ Advanced Excel formulas
- ✅ Pivot table mastery
- ✅ Statistical analysis
- ✅ Data visualization
- ✅ Dashboard design
- ✅ Interactive reporting

</td>
<td width="50%">

**Business Skills**
- ✅ HR analytics understanding
- ✅ Attrition analysis
- ✅ Retention strategy development
- ✅ Data-driven decision making
- ✅ Stakeholder communication
- ✅ Business insight generation

</td>
</tr>
</table>

### Key Takeaways
- 📊 Built comprehensive understanding of **HR analytics workflows**
- 🎯 Learned to identify **actionable patterns** in workforce data
- 📈 Developed skills in **predictive indicators** for attrition
- 💼 Gained experience creating **executive-ready dashboards**
- 🧠 Enhanced ability to **translate data into business recommendations**

---

## 🛠️ Technical Requirements

### Software
- **Microsoft Excel 2016 or later** (recommended)
- Excel 2013 (minimum, with some limitations)

### System Requirements
- Windows 10/11 or macOS
- Minimum 4GB RAM (8GB recommended)
- 100MB free disk space

### Features Required
- Pivot Tables & Charts
- Slicers & Timelines
- Conditional Formatting
- Advanced Formulas

---

## 📚 Methodology

### 1. Data Collection & Understanding
```
➤ Source dataset from Kaggle
➤ Review data dictionary
➤ Understand business context
➤ Identify key variables
```

### 2. Data Cleaning & Preparation
```
➤ Handle missing values (imputation/removal)
➤ Remove duplicates
➤ Standardize formats
➤ Create derived variables
➤ Validate data integrity
```

### 3. Exploratory Data Analysis
```
➤ Calculate descriptive statistics
➤ Identify distributions
➤ Detect outliers
➤ Analyze correlations
➤ Segment data by categories
```

### 4. Dashboard Development
```
➤ Design KPI framework
➤ Create pivot tables
➤ Build visualizations
➤ Add interactivity
➤ Optimize user experience
```

### 5. Insight Generation
```
➤ Interpret findings
➤ Identify patterns
➤ Develop recommendations
➤ Document insights
➤ Present to stakeholders
```

---

## 🔮 Future Enhancements

- [ ] Integrate predictive modeling (logistic regression)
- [ ] Add employee segmentation (RFM-style analysis)
- [ ] Implement cost-of-attrition calculator
- [ ] Create automated alert system for high-risk employees
- [ ] Add comparison with industry benchmarks
- [ ] Develop retention ROI calculator
- [ ] Include sentiment analysis from exit interviews
- [ ] Build Power BI version for advanced analytics

---

## 📖 Related Concepts

### HR Analytics Metrics

| Metric | Formula | Purpose |
|--------|---------|---------|
| **Attrition Rate** | (Employees Left / Total Employees) × 100 | Overall turnover |
| **Retention Rate** | (Employees Stayed / Total Employees) × 100 | Workforce stability |
| **Time to Fill** | Average days to fill vacant position | Hiring efficiency |
| **Cost per Hire** | Total recruitment costs / Hires made | Recruiting ROI |
| **Employee Lifetime Value** | Avg tenure × Avg productivity value | Long-term value |

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. 🍴 Fork the repository
2. 🔧 Create a feature branch (`git checkout -b feature/Enhancement`)
3. 💾 Commit changes (`git commit -m 'Add Enhancement'`)
4. 📤 Push to branch (`git push origin feature/Enhancement`)
5. 🔃 Open a Pull Request

### Ideas for Contributions
- Additional visualizations
- Enhanced statistical analysis
- Predictive modeling integration
- Industry benchmark comparisons
- Automated reporting features

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Diwan Farhan**

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-decodedbyfarhan.tech-blue?style=for-the-badge&logo=google-chrome)](https://decodedbyfarhan.tech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-farhan16-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/farhan16/)
[![GitHub](https://img.shields.io/badge/GitHub-farhann--16-181717?style=for-the-badge&logo=github)](https://github.com/farhann-16)

</div>

---

## 🙏 Acknowledgments

- Dataset source: **Kaggle HR Analytics Community**
- Inspired by real-world HR challenges
- Thanks to data analytics community for best practices
- Special appreciation for open-source contributors

---

## 📊 Project Impact

<div align="center">

![Excel Analysis](https://img.shields.io/badge/Excel_Analysis-Professional-green?style=for-the-badge)
![Data Points](https://img.shields.io/badge/Data_Points-1500+-orange?style=for-the-badge)
![Insights](https://img.shields.io/badge/Insights-8+-blue?style=for-the-badge)
![Recommendations](https://img.shields.io/badge/Recommendations-6-red?style=for-the-badge)

</div>

---

<div align="center">

### ⭐ If this project helped you understand HR Analytics, give it a star!

**Made with ❤️ and lots of data analysis by Farhan**

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=farhann-16.hr-attrition-analysis)
![GitHub stars](https://img.shields.io/github/stars/farhann-16/Data_Science?style=social)

---

### 💼 Ready to reduce employee attrition? Start exploring the dashboard!

</div>

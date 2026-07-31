# 👥 HR Analytics Dashboard
**Turning Workforce Data into People Decisions**

`Power BI` `Power Query` `DAX` `CSV`

---

## 📌 Table of Contents
- [🎯 Project Overview](#-project-overview)
- [🖼️ Dashboard Preview](#️-dashboard-preview)
- [📊 KPIs Tracked](#-kpis-tracked)
- [📈 Charts & Visualizations](#-charts--visualizations)
- [💼 Business Goals](#-business-goals)
- [🔧 Project Workflow](#-project-workflow)
- [💡 Key Insights](#-key-insights)
- [🗂️ Dataset Info](#️-dataset-info)
- [🚀 How to Use](#-how-to-use)
- [👨‍💻 About Me](#-about-me)

---

## 🎯 Project Overview
**Goal:** Build an interactive **HR Analytics Dashboard** in Microsoft Power BI — using Power Query for data cleaning and DAX for calculated metrics — to help HR teams monitor headcount, attrition, and workforce demographics at a glance.

The dashboard gives HR leaders and business stakeholders a single view to track who's joining, who's leaving, and why — broken down by department, salary band, job role, gender, age group, and experience.

| 📋 Category | 📝 Details |
|---|---|
| Tool | Microsoft Power BI |
| Data Source | CSV File (IBM HR Dataset) |
| Records | 1,480 employees |
| Report Type | Workforce & Attrition Dashboard |
| Domain | Human Resources / People Analytics |

---

## 🖼️ Dashboard Preview
📊 *Full interactive dashboard built in Microsoft Power BI*

---

## 📊 KPIs Tracked

| 👤 1.478K | ✅ 1.239K | 🚪 239 | 📉 16.2% | 🎂 36.95 | 🧳 7.01 |
|---|---|---|---|---|---|
| Total Employees | Active Employees | Attrition Count | Attrition Rate | Average Age | Avg Experience (Yrs) |

### 📌 KPI Descriptions
- 👤 **Total Employees** — Overall headcount across the organization
- ✅ **Active Employees** — Employees currently retained (non-attrited)
- 🚪 **Attrition Count** — Total employees who exited the company
- 📉 **Attrition Rate** — % of workforce lost to attrition
- 🎂 **Average Age** — Mean age of the workforce
- 🧳 **Avg Experience** — Mean total years of professional experience

---

## 📈 Charts & Visualizations

| # | 📊 Chart | 📝 Description |
|---|---|---|
| 1 | 🍩 Attrition by Department | Donut chart — attrition share across Operations, Sales, Administration, IT, HR, Marketing & Finance |
| 2 | 💰 Attrition by Salary Slab | Bar chart — attrition split (Yes/No) across 0-3, 3-6, 6-10 & 10+ LPA bands |
| 3 | 🧑‍💼 Attrition by Job Role & Satisfaction | Matrix — job role vs satisfaction score (1–4) with row totals |
| 4 | 📶 Age Group Distribution | Column chart — headcount across 18-25, 26-35, 36-45, 46-55 & 55+ |
| 5 | ⚧️ Attrition by Gender | Pie chart — Male vs Female attrition split |
| 6 | 📈 Attrition Trend by Experience | Area chart — attrition pattern across years of total experience |
| 7 | 🏢 Department-Wise Employee Count | Bar chart — headcount distribution by department |
| 8 | 🎚️ Age Group Slicer | Interactive filter (18-25 / 26-35 / 36-45 / 46-55 / 55+) driving all visuals |

---

## 💼 Business Goals

### 🎯 Strategic Objectives & Expected Impact

| 🎯 Goal | 📝 Description |
|---|---|
| 📉 Reduce Attrition | Spot high-risk departments and roles early to act before employees exit |
| 💰 Compensation Review | Use salary-slab attrition trends to guide pay-band adjustments |
| 😊 Employee Satisfaction | Track satisfaction scores by job role to flag disengagement hotspots |
| 🧑‍🤝‍🧑 Workforce Planning | Use age & experience trends to plan succession and hiring pipelines |

### ✅ Key Business Decisions Enabled
- 🚩 Flag departments with above-average attrition for retention action
- 💵 Re-evaluate pay bands where attrition is disproportionately high
- 🧑‍💼 Identify job roles with low satisfaction scores for targeted engagement plans
- ⚖️ Monitor gender-wise attrition to support DEI initiatives
- 🕒 Use experience-based attrition trend to spot early-tenure flight risk
- 🎚️ Filter by age group to tailor HR policies for different generations

---

## 🔧 Project Workflow

```
📋 Business          🔍 Understanding      🔗 Data Connection
   Requirement    →     of Data         →    (CSV → Power Query)
   Gathering

        ↓

🧹 Data Cleaning      🏗️ Data Modelling     ➕ DAX Measures
   & Quality Check  →   (Relationships)  →   (Attrition Rate,
   (Power Query)                              Avg Age, Avg Exp)

        ↓

📊 Visuals &          🎚️ Slicers &          📈 Insights &
   Dashboard       →    Interactivity   →     Reporting ✅
   Layout
```

---

## 💡 Key Insights
🔍 **What the data revealed after analysis:**

- 🏢 **Operations is the largest department** at 540 employees, but has the **lowest attrition rate (~8.3%)** — a stable, well-retained team.
- ⚠️ **Human Resources sees the highest attrition rate** at ~26.8%, followed closely by Sales at ~25.2%, despite being smaller teams.
- 🔥 **Overtime is a major attrition driver** — employees working overtime leave at ~31.2%, roughly **3x the rate** of those who don't (~10.4%).
- 🧪 **Laboratory Technician tops attrition by headcount** (61 exits), followed by Sales Executive (58) and Research Scientist (48).
- ⚧️ **Attrition is fairly balanced by gender** — Male ~17.0% vs Female ~15.2%, showing no extreme skew.
- 💰 **10+ LPA earners still churn** — the highest salary band shows the second-highest attrition rate (~19.2%), suggesting money alone isn't the retention lever.
- 📶 **26-35 age group dominates the workforce**, making early-career engagement a priority for long-term retention.

---

## 🗂️ Dataset Info

<details>
<summary>📁 Dataset Columns — Click to expand</summary>

`EmpID` `Age` `AgeGroup` `Attrition` `BusinessTravel` `DailyRate` `Department` `DistanceFromHome(KM)` `Education` `EducationField` `EmployeeCount` `EmployeeNumber` `EnvironmentSatisfaction` `Gender` `JobInvolvement` `JobLevel` `JobRole` `JobSatisfaction` `MaritalStatus` `MonthlyIncome` `SalarySlab` `HourlyRate` `NumCompaniesWorked` `Over18` `OverTime` `SalaryHike %` `PerformanceRating` `RelationshipSatisfaction` `StandardWorkingHours` `StockOptionLevel` `TotalExperience(Years)` `TrainingsLastYear` `WorkLifeBalance` `YearsatCompany` `YearsinCurrentRole` `YearsSincePromotion` `YearsWithCurrManager`

</details>

---

## 🚀 How to Use

```bash
# 1. Clone this repository
git clone https://github.com/kabirshaikh232/hr-analytics-dashboard.git

# 2. Open the Power BI file
HR_Analytics_Dashboard.pbix

# 3. If data doesn't load, go to:
#    Home → Transform Data → Data Source Settings
#    → Update the CSV file path to your local machine

# 4. Use the slicers to filter by:
#    → Age Group (18-25, 26-35, 36-45, 46-55, 55+)
#    → Department (Administration, Sales, HR, IT, Marketing, Operations, Finance)
```

**Requirements:** Microsoft Power BI Desktop (latest version recommended). CSV data source must remain in the same folder or the path updated in Power Query.

---

## 👨‍💻 About Me
**Kabir Shaikh** | Data Analyst

🎓 BCA Graduate (2025) | 🎓 Pursuing MCA @ D Y Patil Technical & Agriculture University, Kolhapur

🔗 [LinkedIn](https://www.linkedin.com/in/kabirshaikh232/) · 🐙 [GitHub](#) · 📧 [Email](shaikhkabir232@gmail.com)

⭐ *If this project helped you, please give it a star!*

Made with ❤️ and lots of DAX measures

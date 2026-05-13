<!-- HEADER BANNER -->
<div align="center">

# 🏢 HR Analytics Dashboard
### Workforce Attrition Intelligence | Enterprise-Grade People Analytics

[![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://microsoft.com/excel)
[![HR Analytics](https://img.shields.io/badge/HR_Analytics-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Data Visualization](https://img.shields.io/badge/Data_Visualization-E63946?style=for-the-badge&logo=chartdotjs&logoColor=white)](#)
[![Business Intelligence](https://img.shields.io/badge/Business_Intelligence-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](#)
[![MIT License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge&logo=github)](CONTRIBUTING.md)
[![Dataset](https://img.shields.io/badge/Dataset-2%2C925_Employees-blue?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)](#)

*Turning workforce data into retention strategy — one KPI at a time.*

[View Dashboard](#dashboard-preview) · [Key Insights](#insights--findings) · [Business Recommendations](#business-recommendations) · [Contact](#author)

</div>

---

## 📋 Project Overview

This HR Analytics Dashboard is an **enterprise-grade workforce intelligence solution** built in Microsoft Excel, analyzing attrition patterns across **2,925 employees** over a 4-year hiring window (2020–2023). 

The dashboard translates raw HR data into actionable executive insights — identifying the organizational conditions that drive employee departures and quantifying the risk of doing nothing. It is designed to speak both to **HR business partners** (in workforce language) and **C-suite stakeholders** (in cost and risk language).

> **One critical finding from this analysis:** Single employees working overtime leave at a rate of **exactly 50%** — a predictable, preventable organizational failure affecting 258 employees and representing millions in annual replacement cost.

---

## ❗ Business Problem

Organizations lose an average of **1.0–2.0× an employee's annual salary** every time someone leaves — through recruiting fees, lost productivity, onboarding costs, and institutional knowledge gaps. At an overall attrition rate of **16.82%**, this organization is experiencing nearly 1 in 6 employees departing annually.

**The core challenge:** HR teams often track *that* employees leave, but struggle to identify *who is about to leave*, *why they leave*, and *what would cost-effectively keep them*.

This dashboard directly addresses that gap by:
- Identifying the highest-risk employee segments before they resign
- Quantifying the relative strength of different attrition drivers
- Translating workforce trends into prioritized business recommendations

---

## 🎯 Objectives

- ✅ Measure and benchmark overall attrition rate against industry context
- ✅ Identify the top demographic, behavioral, and operational attrition drivers
- ✅ Segment the workforce by flight risk using multi-variable analysis
- ✅ Surface hidden compound risk patterns invisible in single-variable analysis
- ✅ Deliver executive-ready insights with prioritized, actionable recommendations

---

## 📊 Dataset Overview

| Attribute | Value |
|---|---|
| **Total Records** | 2,925 employees |
| **Attrition Cases** | 492 (16.82%) |
| **Active Employees** | 2,433 (83.18%) |
| **Hiring Period** | 2020 – 2023 |
| **Departments** | Sales, R&D, HR |
| **Total Columns** | 20 features |

### 📁 Data Dictionary

| Column | Data Type | Description |
|---|---|---|
| `Attrition` | Categorical (Yes/No) | Whether employee left the organization |
| `Hiring Year` | Integer | Year the employee was hired (2020–2023) |
| `Business Travel` | Categorical | Travel frequency: Non-Travel / Travel_Rarely / Travel_Frequently |
| `Department` | Categorical | HR, R&D, Sales |
| `Education Field` | Categorical | Employee's educational background |
| `emp no` | String (ID) | Unique employee identifier (anonymized) |
| `Gender` | Categorical | Female / Male |
| `Job Role` | Categorical | 9 distinct roles from Sales Rep to Research Director |
| `Marital Status` | Categorical | Single / Married / Divorced |
| `Over Time` | Categorical (Yes/No) | Whether employee regularly works overtime |
| `Age` | Integer | Employee age (18–60) |
| `Education` | Ordinal (1–5) | Education level: 1=High School → 5=Doctoral |
| `Job Involvement` | Ordinal (1–4) | How engaged employee feels in their role |
| `Job Level` | Ordinal (1–5) | Seniority level: 1=Entry → 5=Executive |
| `Job Satisfaction` | Ordinal (1–4) | Self-reported satisfaction with role |
| `Num Companies Worked` | Integer | Number of prior employers |
| `Performance Rating` | Ordinal (3–4) | Annual performance score |
| `Relationship Satisfaction` | Ordinal (1–4) | Satisfaction with workplace relationships |
| `Total Working Years` | Integer | Total years of professional experience |
| `Work Life Balance` | Ordinal (1–4) | Self-reported work-life balance score |

---

## 📐 KPI Definitions

| KPI | Formula | Interpretation |
|---|---|---|
| **Attrition Rate** | (Employees Left / Total Employees) × 100 | Lower is better; benchmark: 10–15% is healthy |
| **Overtime Attrition Multiplier** | OT-Yes Rate / OT-No Rate | Shows how much overtime amplifies exit risk |
| **Role-Level Attrition** | Leavers in Role / Total in Role × 100 | Identifies structurally broken roles |
| **Compound Risk Rate** | Attrition for (Condition A AND Condition B) | Surfaces non-obvious high-risk segments |
| **Attrition Gap (Avg Tenure)** | Avg Tenure (Stayers) − Avg Tenure (Leavers) | Quantifies experience lost per departure |

---

## 🖥️ Dashboard Features

- **Executive KPI Cards** — Attrition Rate, Total Employees, Active Employees, Attrition Count at a glance
- **Department Attrition Breakdown** — Bar chart comparison across HR, Sales, R&D
- **Age Group Analysis** — Cohort-level attrition by decade bracket (18–60)
- **Overtime Impact View** — Side-by-side attrition rate for OT vs Non-OT employees
- **Job Role Risk Matrix** — All 9 roles ranked by attrition rate
- **Work-Life Balance Correlation** — Attrition by WLB self-rating (1–4 scale)
- **Gender & Marital Status Segmentation** — Demographic breakdown with attrition overlay
- **Business Travel Analysis** — Three-tier travel frequency vs. attrition comparison
- **Interactive Slicers** — Filter by Department, Gender, Marital Status, Overtime
- **Pivot-Based Architecture** — Full Excel Pivot Table backend for auditability

---

## 📸 Dashboard Preview

> 📌 *Screenshots coming soon — dashboard images will be added to `/assets/` folder.*

| View | Description |
|---|---|
| `overview.png` | Executive summary KPI cards + department overview |
| `role_analysis.png` | Job role attrition ranking with risk indicators |
| `demographic_drilldown.png` | Age, gender, marital status breakdown |

---

## 💡 Insights & Findings

### 🔴 Critical Findings

**1. Single Employees Working Overtime: 50% Attrition Rate**  
The highest-risk compound segment in the entire dataset — 258 employees at 50% exit probability. This is not a coincidence; it is a structural failure of workload management.

**2. Entry-Level (Job Level 1) Attrition at 27.67%**  
The organizational base is leaking. Entry-level exits cost institutional knowledge, increase mid-level management burden, and signal broken onboarding systems.

**3. Sales Representatives Exiting at 40.48%**  
The frontline revenue generation role has the highest role-level attrition in the organization — a direct threat to pipeline health and client relationships.

### 🟠 High-Priority Findings

**4. Frequent Business Travel: 25.64% Attrition**  
Nearly identical risk level to overtime, yet completely absent from current retention strategies. Frequent travelers represent an underserved, high-risk workforce segment.

**5. Low Job Involvement (Score 1): 33.73% Attrition**  
The single strongest satisfaction-related predictor of exits. Employees who don't feel engaged leave at 3× the rate of highly involved colleagues.

**6. Younger Workforce (18–25): 37.50% Attrition**  
The next generation of talent is the most volatile. Without structured onboarding and career development, early-career retention will remain systemically poor.

### Summary Attrition Table

| Segment | Attrition Rate | vs. Company Avg | Risk Level |
|---|---|---|---|
| Single + Overtime (compound) | **50.00%** | +33.18pp | 🔴 Critical |
| Sales Representative | **40.48%** | +23.66pp | 🔴 Critical |
| Age 18–25 | **37.50%** | +20.68pp | 🔴 Critical |
| Low Job Involvement | **33.73%** | +16.91pp | 🔴 Critical |
| Overtime Workers | **31.32%** | +14.50pp | 🔴 Critical |
| Low WLB (Score 1) | **30.82%** | +14.00pp | 🔴 Critical |
| Entry Level (Job Level 1) | **27.67%** | +10.85pp | 🔴 Critical |
| Single Employees | **26.02%** | +9.20pp | 🟠 High |
| Frequent Travelers | **25.64%** | +8.82pp | 🟠 High |
| Lab Technicians | **25.54%** | +8.72pp | 🟠 High |
| Human Resources Role | **23.08%** | +6.26pp | 🟠 High |
| Sales Department | **20.83%** | +4.01pp | 🟠 High |
| HR Department | **19.05%** | +2.23pp | 🟡 Elevated |
| Overall Company | **16.82%** | — | Baseline |
| R&D Department | **14.80%** | −2.02pp | 🟢 Below Avg |
| Non-Travel Employees | **8.67%** | −8.15pp | 🟢 Stable |

---

## ✅ Business Recommendations

| Priority | Recommendation | Target Segment | Estimated Impact |
|---|---|---|---|
| 🔴 P1 | Immediate manager outreach + workload audit for Single + Overtime employees | 258 employees at 50% risk | Prevent ~129 departures |
| 🔴 P1 | Sales Representative incentive structure review | ~84 at-risk Sales Reps | Protect revenue pipeline |
| 🔴 P1 | Redesign entry-level onboarding with 90/180/360-day milestones | All Level 1 employees | Reduce L1 attrition by target 8pp |
| 🟠 P2 | Introduce travel reduction options as a negotiable retention lever | Frequent travelers | Address 25.64% flight risk |
| 🟠 P2 | Launch "job crafting" workshops for low job involvement employees | Score 1–2 employees | Engagement-linked attrition reduction |
| 🟠 P2 | Proactive pulse surveys for 2022 hiring cohort (3-year risk window approaching) | 789 employees | Early warning system for largest cohort |
| 🟡 P3 | Establish technical career ladders for Technical Degree / Lab Technician roles | STEM workforce | Address 24–25% attrition in specialized talent |
| 🟡 P3 | Create L3 → L4 promotion transparency framework | Mid-senior employees | Close the career progression gap |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Primary analysis, dashboard, and visualization environment |
| **Excel Pivot Tables** | Underlying data aggregation engine for all KPIs |
| **Excel Charts** | Bar, column, line, and KPI card visualizations |
| **Excel Slicers** | Interactive filtering across all dashboard views |
| **Conditional Formatting** | Risk-level color coding across data tables |

---

## 📁 Project Structure

```
HR-Analytics-Dashboard/
│
├── 📄 README.md                          ← This file
├── 📄 LICENSE                            ← MIT License
├── 📄 CHANGELOG.md                       ← Version history
│
├── 📂 data/
│   ├── HR-Analytics-Dashboard.xlsx       ← Main dashboard file
│   └── data_dictionary.md               ← Column definitions & scales
│
├── 📂 assets/
│   ├── dashboard_overview.png            ← Main dashboard screenshot
│   ├── role_analysis.png                 ← Job role attrition view
│   └── demographic_drilldown.png         ← Age/gender/marital breakdown
│
├── 📂 analysis/
│   ├── HR_Analytics_Full_Report.md       ← Consulting-grade findings report
│   └── attrition_risk_model.xlsx         ← Composite risk score calculator
│
└── 📂 presentation/
    └── HR_Analytics_Executive_Summary.pdf ← Board-ready one-pager
```

---

## 🔮 Future Enhancements

| Enhancement | Description | Tools |
|---|---|---|
| **Predictive Attrition Model** | Logistic regression scoring each employee 0–100 flight risk | Python (scikit-learn) |
| **Power BI Migration** | Rebuild dashboard with live data refresh and drill-through | Microsoft Power BI |
| **Cost of Attrition Calculator** | Dynamic calculator: input salary bands → output annual attrition cost | Excel / DAX |
| **Sentiment Analysis Integration** | Layer engagement survey NLP scores onto attrition risk | Python (NLTK/VADER) |
| **Diversity Equity Analytics** | Gender × Job Level promotion equity heatmap | Power BI / Python |
| **Manager Quality Proxy Analysis** | Relationship Satisfaction + Job Involvement → manager risk scoring | Excel |
| **Time-Series Attrition Trending** | Monthly/quarterly attrition movement analysis using hiring year cohorts | Python / Excel |

---

## 📈 Business Impact

This analysis, if acted upon, has the potential to deliver measurable organizational value:

- **Preventing 50% attrition in the Single + Overtime segment** (129 employees retained) × estimated average replacement cost of $50K = **$6.45M in avoided cost**
- **Reducing Sales Representative attrition by 10pp** (8 representatives retained) × $75K avg replacement cost = **$600K in avoided cost**
- **5pp overall attrition reduction** across 2,925 employees = 146 fewer departures × $50K avg cost = **$7.3M in annual savings**

*Note: Replacement cost estimates use the industry-standard 1.0–1.5× annual salary multiplier from SHRM Attrition Cost Framework.*

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:

- **HR Domain Expertise** — understanding what drives attrition, how to interpret workforce KPIs, and what actions HR business partners can realistically implement
- **Multi-Variable Analysis** — moving beyond single-factor analysis to identify compound risk segments (Single + Overtime = 50%)
- **Business Storytelling** — translating percentage points into cost impact and prioritized action plans
- **Data Validation** — cross-checking all reported figures against raw source data for accuracy
- **Executive Communication** — structuring findings for multiple audiences (HR teams vs. C-suite)

---

## 👤 Author

**[Shravan Shukla]**

📧 [shravanshukla982@gmail.com]  
💼 [https://www.linkedin.com/in/ShuklaShravan]  
🐙 [github.com/ShravanShukla-ai]

*Data Analyst | People Analytics | Business Intelligence | Microsoft Excel*

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/your-analysis`
3. Commit your changes: `git commit -m 'Add: [brief description]'`
4. Push to the branch: `git push origin feature/your-analysis`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

Free to use, modify, and distribute with attribution.

---

<div align="center">

**⭐ If this project helped you, please give it a star — it helps others find it!**

*Built with analytical precision and business intent.*

</div>

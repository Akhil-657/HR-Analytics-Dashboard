# 📊 HR Analytics Dashboard (Power BI)

An interactive Power BI dashboard that analyzes employee attrition and workforce demographics to help HR teams understand **who is leaving, from where, and why**.

![HR Analytics Dashboard](images/HR_Analytics_Dashboard.png)

## 🎯 Objective
To identify attrition patterns across departments, age groups, gender, and education fields, so that HR can make data-driven retention decisions.

## 📌 Key Metrics
| Metric | Value |
|---|---|
| Overall Employees | 1,470 |
| Attrition (Employees Left) | 237 |
| Attrition Rate | 16.12% |
| Active Employees | 1,233 |
| Average Age | 37 |

## 🔍 Dashboard Highlights
- **Department-wise Attrition:** R&D accounts for the most attrition (133, 56.12%), followed by Sales (92, 38.82%) and HR (12, 5.06%).
- **Employees by Age Group:** The 25–34 group is the largest workforce segment (554 employees), shown with a gender split across all age bands (Under 25, 25–34, 35–44, 45–54, Over 55).
- **Job Satisfaction Rating:** Role-wise breakdown of satisfaction scores (1–4) for roles like Sales Executive, Research Scientist, Manager, etc.
- **Education Field-wise Attrition:** Life Sciences (89) and Medical (63) have the highest attrition.
- **Attrition by Gender across Age Groups:** Donut charts showing the gender split of attrition in each age band.
- **Education Level Slicers:** Filter the whole dashboard by Associate's, Bachelor's, Master's, Doctoral, or High School.

## 💡 Key Insights
- The **25–34 age group has the highest attrition (112 of 237, ~47%)**, so early-career employees are the biggest retention risk.
- **R&D contributes over half of total attrition**, making it the priority department for retention efforts.
- Employees from **Life Sciences and Medical** backgrounds show the highest attrition.
- Attrition is lowest in the **Above 55 group (11 employees)**, indicating higher stability among senior employees.

## 🛠️ Tools & Technologies
- **Power BI Desktop**
- **DAX** (measures and calculated columns)
- **Power Query** (data cleaning and transformation)

## 📁 Project Structure
```
├── HR_Analytics.pbix        # Power BI dashboard file
├── dataset/                 # Raw data (CSV)
├── images/                  # Dashboard screenshots
└── README.md
```

## 🚀 How to Use
1. Clone this repository
2. Open `HR_Analytics.pbix` in Power BI Desktop
3. Use the education-level slicers at the top to filter the dashboard

## 👤 Author
**Akhilesh Yadav**
Aspiring Data Analyst | SQL • Python • Excel • Power BI
📍 Mumbai, India
🔗 [LinkedIn](your-linkedin-link) | [GitHub](your-github-link)

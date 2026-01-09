# 📊 COVID-19 Data Analysis & Interactive Excel Dashboard

## 📌 Project Overview
This project focuses on end-to-end analysis of COVID-19 data using ETL techniques, Excel-based analytics, and interactive dashboarding.  
The goal is to transform raw COVID-19 datasets into meaningful insights and present them in a professional Excel dashboard.

This project is beginner-friendly and demonstrates practical data analytics skills using real-world datasets.

---

## 📂 Datasets Used
The following datasets were used in this project:

- **COVID-19 Case Data**
  - State-wise daily confirmed, recovered, and death counts
- **Vaccination Data**
  - State-wise vaccination statistics
- **Testing Data**
  - State-wise COVID-19 testing information

All datasets were cleaned, standardized, and merged for analysis.

---

## 🛠 Tools & Technologies
- Microsoft Excel  
  - Pivot Tables  
  - Excel formulas  
  - Charts & Visualizations  
  - Conditional Formatting  
  - Slicers & Timelines  
- Google Colab (for initial data preparation)
- CSV file format

---

## 🔄 Part I: ETL (Extract, Transform, Load)

### Extract
- Loaded COVID-19 cases, vaccination, and testing datasets
- Inspected structure, data types, and missing values

### Transform
- Standardized date formats
- Created derived columns:
  - Daily New Cases
  - Case Fatality Rate (CFR)
  - Recovery Rate
  - Positive Test Rate
- Handled missing and inconsistent values
- Aligned state names across datasets
- Created pre- and post-vaccination indicators

### Load
- Created a final cleaned dataset: `covid_summary_final.csv`
- Prepared data for Excel analysis and dashboarding

---

## 📊 Part II: Excel Data Analysis

The following analyses were performed using Excel:

- Missing data handling
- Daily new cases calculation
- State-wise case proportion
- Month-wise and weekday-wise trend analysis
- Positive rate calculation
- Case Fatality Rate (CFR) trend analysis
- Pre vs post vaccination infection comparison
- Identification of critical states using advanced filters
- Time series forecasting
- State-specific and date-based queries using INDEX & MATCH
- Interactive state selection using Data Validation

Each analysis was supported with pivot tables and visualizations.

---

## 📈 Part III: Excel Dashboard

### 🎯 Dashboard Objective
To provide a comprehensive and interactive view of the COVID-19 situation across states, enabling users to analyze trends, compare regions, and identify risk patterns.

### 🧩 Dashboard Sections
- COVID-19 Case Summary (KPIs)
- Vaccination Progress Tracker
- Testing Analysis
- Trend Analysis (Cases, Deaths, Recoveries)
- Statewise Impact Overview
- Advanced Statistical Analysis (CFR, Pre/Post Vaccination)
- Interactive Filters (State & Date)

---

## 🔍 Key Insights
- COVID-19 cases show clear wave patterns over time
- Case Fatality Rate declined and stabilized as healthcare response improved
- Post-vaccination period coincided with a major COVID wave
- High positivity rates indicate potential under-testing in some states
- Significant regional differences exist in COVID-19 impact

---

## ⚠️ Data Limitations
- Age-group vaccination data was not available
- Population data was approximated where required
- Short-term infection trends are influenced by variants and policy changes

All limitations were clearly documented to maintain analytical integrity.

---

## 📁 Project Structure
COVID-19-Data-Analysis/
│
├── data/
│ ├── covid_19_india.csv
│ ├── covid_vaccine_statewise.csv
│ └── StatewiseTestingDetails.csv
│
├── analysis/
│ └── covid_summary_final.csv
│
├── COVID_Dashboard.xlsx
└── README.md


---

## 🚀 How to Use
1. Open `COVID_Dashboard.xlsx`
2. Use slicers to filter by state and date
3. Explore KPIs, trends, and comparisons interactively

---

## 🎓 Learning Outcomes
- Understanding of ETL workflows
- Hands-on experience with real-world datasets
- Strong Excel analytics and dashboarding skills
- Ability to derive and communicate insights clearly

---

## 🏁 Conclusion
This project demonstrates how raw COVID-19 data can be transformed into actionable insights using Excel.  
The interactive dashboard provides a clear, structured, and professional overview of pandemic trends.

---

## 👤 Author
**Shivam Patidar**  
Data Analyst

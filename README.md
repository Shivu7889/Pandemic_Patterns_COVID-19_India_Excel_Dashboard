📊 COVID-19 Data Analysis & Interactive Excel Dashboard
📌 Project Overview

This project focuses on end-to-end analysis of COVID-19 data using ETL techniques, Excel-based analytics, and dashboarding.
The objective is to transform raw COVID-19 datasets into meaningful insights and present them through a professional, interactive Excel dashboard.

The project covers:

Data extraction and cleaning

Feature engineering and transformations

Exploratory data analysis using Excel formulas and Pivot Tables

Advanced analytical insights

Interactive dashboard creation

This project is designed for beginners in Data Analytics and demonstrates practical, industry-relevant skills.

📂 Datasets Used

The following publicly available datasets were used:

COVID-19 Case Data

State-wise daily confirmed, recovered, and death counts

Vaccination Data

State-wise vaccination statistics

Testing Data

State-wise COVID-19 testing details

All datasets were merged and cleaned to create a unified analytical dataset.

🛠 Tools & Technologies

Microsoft Excel

Pivot Tables

Advanced Excel formulas

Conditional Formatting

Charts & Visualizations

Slicers & Timelines

Google Colab (for initial data preparation)

CSV data format

🔄 Part I: ETL (Extract, Transform, Load)
✔ Extract

Loaded COVID-19 case, vaccination, and testing datasets

Inspected schema, data types, and missing values

✔ Transform

Standardized date formats

Created derived metrics:

Daily New Cases

Case Fatality Rate (CFR)

Recovery Rate

Positive Test Rate

Handled missing and inconsistent values

Aligned state names across datasets

Created pre- and post-vaccination indicators

✔ Load

Generated a final cleaned dataset (covid_summary_final.csv)

Prepared data for Excel-based analysis and dashboarding

📊 Part II: Excel Data Analysis

The following analyses were performed using Excel:

Missing data identification and handling

Daily new cases calculation

State-wise case proportion

Month-wise and weekday-wise trend analysis

Positive rate calculation

Case Fatality Rate (CFR) trend analysis

Pre- vs Post-vaccination infection comparison

Advanced filtering to identify critical states

Time-series forecasting for future cases

State-specific and date-based queries using INDEX & MATCH

Interactive state selection using Data Validation

Each analysis was supported with appropriate charts and pivot tables.

📈 Part III: Excel Dashboard
🎯 Dashboard Objective

To provide a holistic and interactive view of the COVID-19 situation, enabling users to explore trends, compare states, and identify risk patterns.

🧩 Dashboard Sections

COVID-19 Case Summary

Total Confirmed Cases

Active Cases

Recoveries

Deaths

Daily New Cases

Recovery Rate

Vaccination Progress Tracker

State-wise vaccination comparison

Cumulative vaccination trends
(Age-group data not available; limitation clearly stated)

Testing Analysis

Total tests conducted

Positive rate

State-wise testing comparison

Trend Analysis

Daily and monthly case trends

Recovery and death trends

Statewise Impact Overview

Heat maps and bar charts

Comparison of cases, CFR, and recovery rates

Advanced Statistical Insights

CFR trends

Pre- and post-vaccination infection analysis

Identification of hotspots and critical states

Interactive Controls

State slicers

Date filters

Dynamic chart updates

🔍 Key Insights

COVID-19 cases show clear wave patterns, with sharp peaks and gradual declines

CFR declined over time, reflecting improved healthcare response

Post-vaccination periods coincided with major waves, indicating delayed visible impact of vaccination on infections

States with high positivity rates may indicate under-testing

Significant regional disparities exist across states

⚠️ Data Limitations

Age-group vaccination data was not available

State population data was approximated where required

Short-term infection trends are influenced by variants and policy changes

All limitations were explicitly acknowledged to maintain analytical integrity.

📁 Project Structure
📦 COVID-19-Data-Analysis
 ┣ 📂 data
 ┃ ┣ covid_19_india.csv
 ┃ ┣ covid_vaccine_statewise.csv
 ┃ ┗ StatewiseTestingDetails.csv
 ┣ 📂 analysis
 ┃ ┗ covid_summary_final.csv
 ┣ 📊 COVID_Dashboard.xlsx
 ┗ 📄 README.md

🚀 How to Use This Project

Open COVID_Dashboard.xlsx

Use slicers to filter by state and date

Explore trends and KPIs interactively

Refer to pivot tables for deeper analysis

🎓 Learning Outcomes

Hands-on experience with real-world datasets

Strong understanding of ETL concepts

Proficiency in Excel analytics and dashboarding

Ability to communicate insights clearly

Awareness of data limitations and assumptions

🏁 Conclusion

This project demonstrates how raw COVID-19 data can be transformed into actionable insights using Excel.
The interactive dashboard provides a clear, concise, and professional view of pandemic trends and supports informed decision-making.

👤 Author

Shivam Patidar
Data Analyst (Beginner Project)

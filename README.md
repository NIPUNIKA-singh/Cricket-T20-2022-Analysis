# 🏏 End-to-End T20 World Cup Sports Data Analytics

## 📖 Overview

This project is an end-to-end **Sports Data Analytics** solution built using **Python, Pandas, Power BI, Power Query, and DAX**. The objective was to analyse **T20 World Cup cricket data** and transform raw match statistics into interactive dashboards that provide meaningful insights into player performances and team strategies.

Rather than working with a pre-cleaned dataset, this project follows the complete data analytics pipeline, beginning with data collection through web scraping and ending with business insights through data visualisation. It demonstrates practical experience in data extraction, cleaning, transformation, modelling, analysis, and dashboard development.

---

# 🎯 Problem Statement

Cricket generates an enormous amount of data across every match, including batting statistics, bowling records, match results, player performances, strike rates, economy rates, and many other metrics. However, this information is scattered across multiple sources and is difficult to analyse manually.

The goal of this project is to:

* Collect T20 World Cup data from ESPN Cricinfo.
* Clean and transform the raw data.
* Build a structured data model.
* Create an interactive dashboard.
* Identify the best-performing players based on statistical analysis.
* Generate insights that support data-driven decision making.

---

# 📌 Project Objectives

The project aims to:

* Understand the complete Data Analytics workflow.
* Perform web scraping to collect real-world sports data.
* Clean messy datasets using Python.
* Transform data for reporting.
* Build an optimized Power BI data model.
* Create dynamic KPIs using DAX.
* Design professional dashboards.
* Generate actionable insights from cricket statistics.

---

# 🛠️ Tech Stack

| Technology    | Purpose                      |
| ------------- | ---------------------------- |
| Python        | Data Processing              |
| Pandas        | Data Cleaning & Manipulation |
| Requests      | Sending HTTP Requests        |
| BeautifulSoup | Web Scraping                 |
| JSON          | Processing Scraped Data      |
| Power Query   | Data Transformation          |
| Power BI      | Dashboard Development        |
| DAX           | Calculated Measures & KPIs   |

---

# 📂 Project Workflow

## 1️⃣ Requirement Scoping

Before analysing the data, the business requirements were defined.

The objective was to identify the strongest possible T20 playing XI based on statistical performance.

Different player roles were considered, including:

* Opening Batsmen
* Middle Order Batsmen
* Finishers
* All-rounders
* Fast Bowlers

Specific performance metrics such as Strike Rate, Average, Economy Rate, Batting Average, Bowling Average, Boundary Percentage, Dot Ball Percentage, and Match Impact were selected to evaluate players objectively.

---

## 2️⃣ Data Collection (Web Scraping)

The cricket data was collected directly from the **ESPN Cricinfo** website using Python.

The web scraping process included:

* Sending HTTP requests to retrieve webpage content.
* Extracting player profiles.
* Collecting batting statistics.
* Collecting bowling statistics.
* Match summaries.
* Team information.
* Player records.
* Saving extracted information into structured JSON files.

This automated process removed the need for manual data collection and ensured consistent data extraction.

---

## 3️⃣ Data Cleaning & Transformation (Python + Pandas)

Raw web data often contains inconsistencies, duplicates, missing values, and formatting issues.

Using Pandas, the following transformations were performed:

* Removed duplicate records.
* Handled missing values.
* Corrected inconsistent player names.
* Converted data types.
* Renamed columns.
* Merged multiple datasets.
* Created structured tables.
* Filtered unnecessary information.
* Standardized statistical values.

After cleaning, the data became ready for analytical processing.

---

## 4️⃣ Data Transformation (Power Query)

The cleaned dataset was imported into Power BI, where Power Query was used for additional transformations.

Tasks included:

* Splitting columns.
* Merging queries.
* Creating custom columns.
* Removing unnecessary fields.
* Changing data types.
* Formatting tables.
* Preparing fact and dimension tables.

Power Query ensured that the data model remained clean, efficient, and scalable.

---

## 5️⃣ Data Modelling

An optimized star schema was created inside Power BI.

Relationships were established between different tables, such as:

* Player Information
* Batting Statistics
* Bowling Statistics
* Match Details
* Team Details

Proper relationships improved report performance and enabled accurate filtering across visuals.

---

## 6️⃣ DAX Measures

Several DAX measures were created to calculate dynamic metrics used throughout the dashboard.

Examples include:

* Total Runs
* Batting Average
* Strike Rate
* Total Wickets
* Bowling Average
* Economy Rate
* Boundary Percentage
* Dot Ball Percentage
* Matches Played
* Player Rankings

These measures allowed users to analyse performance interactively.

---

## 7️⃣ Dashboard Development

An interactive Power BI dashboard was developed to present insights visually.

The dashboard includes:

* KPI Cards
* Interactive Filters
* Player Comparison
* Team Comparison
* Batting Performance Analysis
* Bowling Performance Analysis
* Top Performers
* Match Statistics
* Dynamic Visualisations
* Drill-through Reports

The dashboard enables users to explore data from multiple perspectives with just a few clicks.

---

# 📊 Key Insights

The dashboard provides valuable insights, including:

* Best Opening Batsmen
* Most Consistent Players
* Highest Strike Rate Players
* Top Finishers
* Best All-rounders
* Leading Wicket Takers
* Most Economical Bowlers
* Boundary Hitters
* Team Performance Comparison
* Overall Best Playing XI

These insights help identify players who consistently deliver strong performances across multiple matches.
### Dashboard Preview: Total 6 Slides but here Starting & Last is displayed.

"C:\Users\LENOVO\Desktop\POWER BI\Cricket DA project\Screenshot (362).png"

"C:\Users\LENOVO\Desktop\POWER BI\Cricket DA project\Screenshot (363).png"

---

# 📁 Project Structure

```
T20-World-Cup-Analytics
│
├── Data
│   ├── Raw Data
│   ├── Cleaned Data
│   └── JSON Files
│
├── Python
│   ├── Web Scraping
│   ├── Data Cleaning
│   └── Data Transformation
│
├── Power BI
│   ├── Dashboard.pbix
│   ├── Images
│   └── Reports
│
├── README.md
└── Requirements.txt
```

---

# 🚀 Skills Demonstrated

Through this project, I gained hands-on experience in:

* Web Scraping
* Data Collection
* Data Cleaning
* Data Wrangling
* Data Transformation
* Exploratory Data Analysis (EDA)
* Data Modelling
* DAX
* Power Query
* Dashboard Design
* Data Visualisation
* Business Intelligence
* Storytelling with Data

---

# 📈 Business Value

This project demonstrates how raw sports data can be converted into actionable insights through data analytics.

The techniques used here can be applied beyond cricket to industries such as finance, healthcare, retail, e-commerce, marketing, and operations, where data-driven decision-making is essential.

---

# 🙌 Acknowledgements

* **ESPN Cricinfo** for providing publicly available cricket statistics.
* **Codebasics** for the project inspiration and learning resources.
* The **Power BI** and **Python** communities for their excellent documentation and open-source libraries.

---

# ⭐ If You Like This Project

If you found this project helpful or interesting, please consider giving it a ⭐ on GitHub. Your support motivates me to build and share more data analytics projects!

Feel free to connect with me for discussions on **Data Analytics, Power BI, Python, SQL, and Business Intelligence**.


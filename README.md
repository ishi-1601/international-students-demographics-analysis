# International Students Demographics Analysis

## Project Overview
This project analyzes the **demographics of international students** to help universities and policymakers understand diversity, enrollment patterns, and funding trends across academic years.  
The workflow combines **data cleaning and integration in Python** with **interactive Power BI dashboards** for visualization.

---

## Objective
- Clean and merge six raw datasets related to international student enrollment.  
- Handle missing values and duplicates to produce a validated, analysis-ready dataset.  
- Build Power BI dashboards to visualize patterns across gender, visa type, funding, and academic level.  
- Derive actionable insights to support institutional and policy-level decision-making.

---

## Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Power BI:** For interactive dashboards  
- **Excel:** Data export and integration layer  
- **Platform:** macOS (with Power BI web for visualization)  
- **Dataset Source:** [Kaggle – International Student Demographics](https://www.kaggle.com/datasets/webdevbadger/international-student-demographics)

---

## Data Cleaning Process
All preprocessing was done in Python inside a Jupyter Notebook:

1. Imported and validated six CSVs:  
   `academic.csv`, `academic_detail.csv`, `field_of_study.csv`, `origin.csv`, `source_of_fund.csv`, and `status.csv`.
2. Checked for missing values and duplicates.  
3. Filled null entries with zeroes to maintain consistency.  
4. Dropped duplicates and verified column integrity.  
5. Exported a unified Excel file (`output_file.xlsx`) with six sheets for Power BI use.

The full reproducible workflow is in `International_Students_Demographics_Cleanup.ipynb`.

---

## Power BI Dashboard Highlights
The Power BI dashboard provides:
- **Visa Type Distribution:** F-Visa (self-sponsored) vs J-Visa (externally sponsored).  
- **Gender Ratio:** Males dominate slightly, though the gap narrows over time.  
- **Marital Status:** Majority are single, showing youth mobility.  
- **Employment Type:** Increasing trend in full-time work participation.  
- **Source of Funds:** Mostly self or family-funded, limited institutional support.  

---

## Key Insights
- Enrollment of international students continues to grow across years.  
- The gender gap in higher education is narrowing.  
- Self-funding remains the dominant financial model.  
- Full-time engagement and OPT participation are increasing steadily.

---

## Outcome
- A **clean, structured, multi-sheet dataset** for analytical and BI use.  
- A **Power BI dashboard** enabling filters by year, academic type, and field of study.  
- Actionable **visual insights** to guide educational diversity strategies.  
- Demonstrates a full **data analytics pipeline** from raw data to dashboard visualization.

---

## 🗂️ Repository Structure

Here’s how the project files are organized:

```plaintext
international-students-demographics-analysis/
│
├── data/  
│   └── (optional) sample CSVs or placeholders  
│
├── notebooks/  
│   └── International_Students_Demographics_Cleanup.ipynb   # Python data cleaning notebook  
│
├── dashboard/  
│   └── International_Students_PowerBI.pbix                  # Power BI visualization file  
│
├── README.md                                                # Project documentation  
└── output_file.xlsx                                         # Cleaned Excel dataset (6 sheets)

# Excel Healthcare Data Analysis

> End-to-end analysis of 55,500+ patient records — from raw data cleaning to an interactive KPI dashboard with documented insights and business recommendations — built entirely in Excel 2019.

---

## Project Overview

This project uses a synthetic healthcare dataset from Kaggle, designed to simulate real-world patient records. I performed data cleaning, exploratory analysis, built an interactive dashboard, and documented key findings with actionable business recommendations.

---

## Dataset

| Detail | Info |
|---|---|
| **Source** | Kaggle (Healthcare Dataset) |
| **Size** | 55,000 patients, 15 columns |
| **Format** | CSV → Excel |

---

## Tools Used

- **Microsoft Excel 2019** — full project (no Power BI, no Python)
- Pivot Tables & Pivot Charts
- Slicers
- Data Cleaning (manual + formula-based)

---

## Process

### 1. Data Cleaning
- Removed duplicates
- Standardised text fields (TRIM, PROPER)
- Handled blank/null values
- Fixed data type inconsistencies in date and numeric columns

### 2. Analysis
Built pivot tables to answer key business questions:

| Analysis | Insight Focus |
|---|---|
| Patient Count by Medical Condition | Which conditions drive the most admissions? |
| Average Billing by Medical Condition | Which conditions cost the most per patient? |
| Patient Count by Age Group | Which age bands are most at risk? |
| Patient Visits by Month | Are there seasonal admission trends? |
| Patient Count by Admission Type | Emergency vs. Elective vs. Urgent breakdown |
| Patient Count by Insurance Provider | Coverage distribution across providers |

### 3. Dashboard
- Built an interactive blue corporate-themed dashboard
- KPI cards showing Total Patients, Top Insurer, Top Medication, Top Condition, and Average Billing
- Slicers for filtering by Gender, Blood Type, and Admission Type

### 4. Key Insights & Recommendations
Documented findings and business recommendations in a dedicated Key Insights sheet.

---

## Dashboard Preview

[![Dashboard Preview](dashboard.png)](dashboard.png)

---

## Key Findings

- All 6 medical conditions (Arthritis, Asthma, Cancer, Diabetes, Hypertension, Obesity) are equally distributed across 55,000 patients with less than 1% variance
- Average billing is remarkably consistent across all conditions, ranging from $25,146 to $26,123 — a difference of only $977 — suggesting treatment costs are uniform
- Middle-aged patients (22–81) account for the majority of admissions, averaging 8,100 patients per age group; extreme age groups show significantly lower admission rates
- Patient admissions peak in August following a gradual increase from May, while February consistently records the lowest admissions
- Cigna leads as the top insurance provider with 11,249 patients, however all 5 providers are remarkably similar ranging from 10,913 to 11,249 — a difference of only 336 patients
- Admissions are equally split across Elective (34%), Urgent (33%), and Emergency (33%), suggesting a balanced distribution across all admission types

---

## Business Recommendations

1. **Seasonal Staffing** — Hospitals should hire additional staff and stock more medical supplies between May and August when admissions consistently increase
2. **Insurance Partnerships** — Since all 5 providers serve nearly equal patient numbers, hospitals should negotiate equal partnership agreements rather than prioritising one provider
3. **Age-Targeted Healthcare Programs** — Since middle-aged patients (22–81) make up the majority of admissions, hospitals should invest in preventive programs targeting this group to reduce future admissions
4. **Billing Transparency** — Since billing is consistent across all conditions averaging $25,500, hospitals should publish standardised treatment cost guides to help patients plan financially
5. **February Capacity Planning** — Despite having the lowest admissions, February should be used for staff training, equipment maintenance, and facility upgrades to prepare for the mid-year surge

---

## Workbook Structure

| Sheet | Description |
|---|---|
| `Raw Data` | Original unmodified dataset |
| `Cleaned Data` | Cleaned and standardised data |
| `Pivot Tables` | All pivot tables used for analysis |
| `Dashboard` | Interactive visual dashboard |
| `Key Insights` | Written findings and business recommendations |

---

## Files in This Repository

| File | Description |
|---|---|
| `Healthcare_Data_Analysis.xlsx` | Full Excel workbook — all 5 sheets |
| `README.md` | Project documentation |

---

## About Me

**Valary Shikanda** — IT Support Specialist & Freelance Data Analyst based in Kenya.  
Passionate about turning raw data into clear, actionable insights using Excel, SQL, and Power BI.

[LinkedIn](https://www.linkedin.com/in/valary-shikanda-aa90162ba)

---

*Built with Microsoft Excel 2019 | Dataset from Kaggle*

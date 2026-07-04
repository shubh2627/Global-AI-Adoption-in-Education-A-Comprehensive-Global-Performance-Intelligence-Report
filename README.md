# Global AI Adoption in Education: A Comprehensive Global Performance Intelligence Report

*A Data-Driven Analysis of Student, Teacher, and School-Level AI Adoption Across Global Education Systems (2015–2026)*

**Author:** Shubham Vitthal Patil
**Program:** Data Analytics with Tableau
**Tools:** Tableau Desktop / Tableau Public

## 📌 Project Overview
This project analyzes global AI adoption trends in education using a dataset of 1,360 monthly records (2015–2026) across 10 countries, 6 regions, and 16 attributes — covering student, teacher, and school-level AI usage, government policy status, curriculum integration, urban/rural equity splits, and gender gaps. The analysis was built end-to-end in Tableau: from raw data cleaning and calculated-field engineering, through worksheet design, to an interactive dashboard and a guided 5-page data story.

## 🔗 Live Links
- **Tableau Public Dashboard:** [View Live Dashboard](https://public.tableau.com/app/profile/shubham.patil4882/viz/Book1_17830728182110/Dashboard1?publish=yes)
- **Tableau Public Story:** [View Live Story](https://public.tableau.com/app/profile/shubham.patil4882/viz/Book1_17830728182110/Story1?publish=yes)
- **Dataset (Kaggle):** [Global AI in Education Dataset 2015–2026](https://www.kaggle.com/datasets/abidhussai512/global-ai-in-education-dataset-20152026)

## 📊 Dashboards
Two linked, interactive dashboards:
1. **Global AI Adoption in Education Dashboard** — geographic overview, adoption-tier breakdown, 2015–2026 growth trend, regional comparison
2. **Global AI Project: Adoption, Usage and Growth** — daily usage intensity by country, student vs. teacher usage, leading AI tool comparison, urban-rural growth split

Screenshots available in [`docs/images/`](./docs/images).

## 📁 Repository Structure
```
├── README.md
├── data/                      # Raw dataset (CSV)
├── docs/
│   ├── Word_Documents/        # Full project documentation set (9 files)
│   └── images/                # Dashboard & story screenshots
├── tableau/                   # Tableau workbook (.twbx)
└── LICENSE
```

## 📄 Documentation
Full project documentation is available in [`docs/Word_Documents/`](./docs/Word_Documents):

| File | Description |
|---|---|
| `01_Project_Initialization_and_Planning.docx` | Problem statement, business question, work breakdown structure, deliverables |
| `02_Data_Quality_Report.docx` | Data quality issues, severity, and resolution plans |
| `03_Raw_Data_Source_Report.docx` | Data collection plan and raw source identification |
| `04_Data_Exploration_and_Preprocessing.docx` | Data cleaning, transformation, and modeling steps |
| `05_Documentation.docx` | Full end-to-end BI project documentation (executive summary, dataset, methodology, insights) |
| `06_Visualization_Report.docx` | Business questions mapped to visualizations and findings |
| `07_Dashboard.docx` | Dashboard design breakdown with screenshots |
| `08_Story.docx` | Tableau Story walkthrough with screenshot |
| `09_Full_Data_Report.docx` | All of the above combined into a single report |

## 🔍 Key Findings
- Global student AI usage grew ~12x, from 4.98% (2015) to 60.75% (2026)
- Adoption is remarkably uniform across all 10 countries (30.60%–31.61% average) — no clear leader or laggard
- Internet penetration and education index do **not** predict adoption speed (r ≈ 0.00 with usage, despite r ≈ 0.98 with each other)
- A formally "Active" government AI policy is a weak predictor of curriculum integration (52.3% Active vs. 51.9% no policy vs. 47.2% Draft)
- The urban-rural usage gap widened from 7.68 pts (2015) to ~13 pts (2018) and has stayed flat since — not closing
- The gender gap in AI usage has held steady between 5.05 and 5.91 points throughout

## 📈 Data Source
`Global_AI_in_Education.csv` — 1,360 monthly records (2015–2026), 10 countries, 6 regions, 16 attributes. Source: [Kaggle](https://www.kaggle.com/datasets/abidhussai512/global-ai-in-education-dataset-20152026).

## 🚀 How to View
1. Clone this repo
2. Open the `.twbx` file in Tableau Desktop, **or**
3. View the live dashboard/story via the Tableau Public links above

## 👤 Author
**Shubham Vitthal Patil**

## 📜 License
This project is licensed under the MIT License — see [LICENSE](./LICENSE) for details.

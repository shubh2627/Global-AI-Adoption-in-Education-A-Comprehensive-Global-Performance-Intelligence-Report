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

Screenshots: [Dashboard 1](./docs/images/Dashboard%201.png) · [Dashboard 2](./docs/images/Dashboard%202.png) · [Story](./docs/images/Story.png)

## 📁 Repository Structure
```
├── README.md
├── data/
│   └── Global AI in Education.csv
├── docs/
│   ├── Report.pdf
│   ├── Project Initialization and Planning.pdf
│   ├── Data Quality Report.pdf
│   ├── Raw Data Source Report.pdf
│   ├── Data Exploration and Preprocessing.pdf
│   ├── Documentation.pdf
│   ├── Visualization Report.pdf
│   ├── Dashboard.pdf
│   ├── Story.pdf
│   └── images/
│       ├── Dashboard 1.png
│       ├── Dashboard 2.png
│       └── Story.png
├── tableau/
│   └── global_ai_education_analysis.twbx
└── LICENSE
```

## 📄 Documentation
Full project documentation is available in [`docs/`](./docs):

| File | Description |
|---|---|
| [Report.pdf](./docs/Report.pdf) | Consolidated report combining all project phases into one document |
| [Project Initialization and Planning.pdf](./docs/Project%20Initialization%20and%20Planning.pdf) | Problem statement, business question, work breakdown structure, deliverables |
| [Data Quality Report.pdf](./docs/Data%20Quality%20Report.pdf) | Data quality issues, severity, and resolution plans |
| [Raw Data Source Report.pdf](./docs/Raw%20Data%20Source%20Report.pdf) | Data collection plan and raw source identification |
| [Data Exploration and Preprocessing.pdf](./docs/Data%20Exploration%20and%20Preprocessing.pdf) | Data cleaning, transformation, and modeling steps |
| [Documentation.pdf](./docs/Documentation.pdf) | Full end-to-end BI project documentation (executive summary, dataset, methodology, insights) |
| [Visualization Report.pdf](./docs/Visualization%20Report.pdf) | Business questions mapped to visualizations and findings |
| [Dashboard.pdf](./docs/Dashboard.pdf) | Dashboard design breakdown with screenshots |
| [Story.pdf](./docs/Story.pdf) | Tableau Story walkthrough with screenshot |

## 🔍 Key Findings
- Global student AI usage grew ~12x, from 4.98% (2015) to 60.75% (2026)
- Adoption is remarkably uniform across all 10 countries (30.60%–31.61% average) — no clear leader or laggard
- Internet penetration and education index do **not** predict adoption speed (r ≈ 0.00 with usage, despite r ≈ 0.98 with each other)
- A formally "Active" government AI policy is a weak predictor of curriculum integration (52.3% Active vs. 51.9% no policy vs. 47.2% Draft)
- The urban-rural usage gap widened from 7.68 pts (2015) to ~13 pts (2018) and has stayed flat since — not closing
- The gender gap in AI usage has held steady between 5.05 and 5.91 points throughout

## 📈 Data Source
[`Global AI in Education.csv`](./data/Global%20AI%20in%20Education.csv) — 1,360 monthly records (2015–2026), 10 countries, 6 regions, 16 attributes. Source: [Kaggle](https://www.kaggle.com/datasets/abidhussai512/global-ai-in-education-dataset-20152026).

## 🚀 How to View
1. Clone or download this repo
2. Open the `.twbx` file in Tableau Desktop, **or**
3. View the live dashboard/story via the Tableau Public links above

## 👤 Author
**Shubham Vitthal Patil**

## 📜 License
This project is licensed under the MIT License — see [LICENSE](./LICENSE) for details.

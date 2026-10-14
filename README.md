# Job Market & Salary Analyzer

Salary analysis of data-field roles (2020-2023) with an interactive Tableau dashboard and Python charts.

**Main finding:** Machine Learning & AI roles have the highest average salary of the 10 job categories (\$178,926), against an overall average of \$150,299. Pay rises steadily with seniority, from \$88,535 for entry-level to \$189,463 for executives.

## Tools Used

- Python (Pandas, NumPy, Plotly)
- SQL (SQLite - data exploration & aggregation)
- Tableau Public
- Google Colab

## Live Dashboard

🔗 [View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/srushti.thakre4507/viz/Job_Market_Analyzer_/Dashboard1?publish=yes)

## Key Insights

- **Machine Learning & AI** has the highest average salary (\$178,926, 1,428 records).
- **Data Science & Research** has the most records (3,014 of 9,355), ahead of Data Engineering (2,260).
- **Seniority pays:** entry-level \$88,535, mid-level \$117,524, senior \$162,356, executive \$189,463.
- **Top-paying titles rest on very few records.** Analytics Engineering Manager (\$399,880) and Data Science Tech Lead (\$375,000) each appear once. Among titles with at least 10 records, the highest paid are AI Architect (12 records, \$250,328), Director of Data Science (29, \$221,365), Machine Learning Software Engineer (13, \$212,908) and Head of Data (33, \$211,187).

## Visualizations

### Tableau Interactive Dashboard

- KPI summary cards (average salary, total categories, highest salary)
- Salary breakdown by category and experience level
- Top 10 highest-paying job titles (several rest on 1-2 records, see Limitations)
- Interactive Work Setting filter (Remote/Hybrid/In-person)

![Tableau Dashboard](tableau_dashboard.png)

---

### Python / Plotly Visualizations (Google Colab)

#### 1. Animated Bar Race
*Number of records per job category by year, 2020-2023 (reflects the dataset's sampling, not necessarily market growth)*

![Animated Bar Race](chart2.png)

#### 2. Parallel Coordinates
*Multi-dimensional job market patterns*

![Parallel Coordinates](chart3.png)

#### 3. Salary Heatmap
*Average salary by category and experience level*

![Salary Heatmap](chart4.png)

#### 4. Bubble Chart
*Average salary by job category; bubble size = number of records*

![Bubble Chart](chart5.png)

---

## Dataset

- Source: Kaggle - Jobs and Salaries in Data Science (Hummaam Qaasim)
- Size: 9,355 records | 12 columns | 2020-2023
- Fields: work year, job title, job category, salary (original currency and USD), employee residence, experience level, employment type, work setting, company location, company size
- Each record is one reported salary, not a live job posting. Counts show how often a role appears in the dataset, not market demand.

## Limitations

- **The data is mostly senior and US-based.** 87% of records are from US companies and 72% are senior roles, so the results describe senior US roles best. Entry-level has only 496 records.
- **Small groups swing averages.** Cloud and Database has 5 records, and several top-paying titles have 1-2.
- **Record counts are not demand.** The bar race and bubble chart show how often a category appears in the dataset, not hiring volume or growth.

# Job Market & Skill-Gap Analyzer

**Main finding:** Machine Learning & AI roles command the highest average salary of the 10 job categories, against an overall average of $150,299. Salary rises steadily with seniority, from entry-level to executive.

## Tools Used
- Python (Pandas, NumPy, Plotly, NetworkX)
- SQL (SQLite — data exploration & aggregation)
- Tableau Public
- Google Colab

## Live Dashboard
🔗 [View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/srushti.thakre4507/viz/Job_Market_Analyzer_/Dashboard1?publish=yes)

## Key Insights
- **Machine Learning & AI roles** command the highest average salaries across all job categories.
- **Salary progression** shows strong growth by experience level, with Executive roles earning significantly more than Entry-level.
- **Top Roles:** Analytics Engineering Manager and Data Science Tech Lead are among the top highest-paying job titles in the dataset.

## Visualizations

### Tableau Interactive Dashboard
- KPI summary cards (average salary, total categories, highest salary)
- Salary breakdown by category and experience level
- Top 10 highest-paying job titles
- Interactive Work Setting filter (Remote/Hybrid/In-person)

![Tableau Dashboard](./tableau_dashboard.png)

---

### Python / Plotly Visualizations (Google Colab)

#### 1. Skills Network Graph
*Relationships between in-demand data skills*
![Skills Network](./chart1.png)

#### 2. Animated Bar Race
*Job category growth from 2020-2023*
![Animated Bar Race](./chart2.png)

#### 3. Parallel Coordinates
*Multi-dimensional job market patterns*
![Parallel Coordinates](./chart3.png)

#### 4. Salary Heatmap
*Average salary by category and experience level*
![Salary Heatmap](./chart4.png)

#### 5. Bubble Chart
*Salary vs demand by job category*
![Bubble Chart](./chart5.png)

---

## Dataset
- Source: Kaggle — Jobs and Salaries in Data Science (Hummaam Qaasim)
- Size: 9,355 records | 12 columns | 2020–2023
- Fields: Job title, category, salary (USD), experience level, 
  company size, work setting, location

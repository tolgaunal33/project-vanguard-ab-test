# 📊 Vanguard A/B Test Analysis — Statistical Analysis Project

A data analysis project evaluating whether Vanguard's new UI/UX design leads to a statistically significant improvement in client process completion rates.

> 🤝 **Group Project** — Completed as part of the Ironhack Data Analytics Bootcamp (team of 3)

---

## 📌 Problem Statement

Vanguard, a US-based investment management company, redesigned its client onboarding process with a new UI. Before rolling it out fully, the company ran an A/B test to determine whether the new design actually improved client experience.

The key question:
> **Does the new UI lead to a statistically significant improvement in process completion rates — and is it cost-effective enough to justify a full rollout?**

---

## 🎯 Objectives

- Define key KPIs to measure the impact of the UI redesign
- Perform Exploratory Data Analysis (EDA) on client behavior data
- Apply statistical hypothesis testing to compare the control and test groups
- Visualize findings in Tableau for non-technical stakeholders
- Provide a data-driven recommendation on whether to proceed with the new design

---

## 🔄 Project Workflow

### 1. Data Preparation & EDA
- Cleaned and merged client datasets (`merged_dataset.xlsx`, `unique_client_dataset.xlsx`)
- Explored client demographics, session behavior, and step completion patterns
- Identified drop-off points across the process funnel

### 2. KPI Definition
Defined the following key performance indicators:
- **Completion Rate** — percentage of clients completing the full process
- **Time Spent per Step** — average time at each stage of the process
- **Error Rate** — frequency of errors or step repetitions per session

### 3. Hypothesis Testing (`Final_vanguard_file_updated.ipynb`)
Applied two statistical tests in Python:
- **One-sided Two-Proportion Z-Test** — to compare completion rates between control and test groups
- **Two-Sample T-Test** — to compare time spent per step between groups

### 4. Visualization
- Built interactive dashboards in **Tableau** to communicate findings to non-technical stakeholders
- Visualized completion funnel, drop-off rates, and KPI comparisons by group

---

## 📈 Key Findings

- The new UI showed a **+3.3% improvement in completion rate** compared to the control group
- However, this improvement fell **below the 5% cost-effectiveness threshold** set by the business
- **Conclusion:** The new design shows promise but requires further refinement before full rollout

---

## 🛠️ Tools & Technologies

| Category | Tools |
|---|---|
| Data Processing | Python (Pandas, NumPy) |
| Statistical Testing | SciPy (Z-test, T-test) |
| Visualization | Tableau, Matplotlib, Seaborn |
| Data | Excel (.xlsx) |
| Environment | Jupyter Notebook, Git |

---

## 📁 Repository Structure

```
project-vanguard-ab-test/
│
├── Final_vanguard_file.ipynb           # Initial analysis notebook
├── Final_vanguard_file_updated.ipynb   # Final analysis with hypothesis testing
├── merged_dataset.xlsx                 # Merged client behavior dataset
├── unique_client_dataset.xlsx          # Unique client records dataset
├── vanguard_project_tableau_updated.twbx  # Tableau workbook
└── README.md
```

---

## 📊 Tableau Dashboard

👉 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/views/vanguard_project_tableau/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 🎤 Presentation

👉 [View Project Presentation on Canva](https://www.canva.com/design/DAGdZ28BIeo/EvMuwzLXWz8y1RFiZ4oxLA/edit)

---

## 👤 Author

**Tolga Unal**
[LinkedIn](https://www.linkedin.com/in/tolgaaunall) · [GitHub](https://github.com/tolgaunal33)

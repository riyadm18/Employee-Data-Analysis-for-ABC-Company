# ABC Company Employee Data Analysis – Python Final Project

## Project Overview

This analysis explores a dataset containing information on 458 employees, including their team, position, age, height, weight, college, and salary. The objective is to generate insights that support business decisions.

## Tasks Completed

###  1. Preprocessing
- Replaced the inconsistent `Height` column values with random numbers between 150 and 180 cm to maintain data consistency.
- Converted `Salary`, `Age`, and `Weight` columns to numeric types, handling missing or invalid values.

### 2. Analysis Tasks

| Task No. | Description |
|----------|-------------|
| 1️⃣ | **Distribution of employees** across each team and their percentage of total headcount. |
| 2️⃣ | **Segregation by position** (e.g., PG, SF, C, etc.). |
| 3️⃣ | **Predominant age group** among employees (categorized). |
| 4️⃣ | **Team and position** with the **highest salary expenditure**. |
| 5️⃣ | **Correlation** between employee **age and salary** using visual and statistical analysis. |

### 3. Visualizations

Each task is represented using appropriate charts created with **Seaborn** and **Matplotlib**:

- Bar plots for team and position distribution.
- Histogram/bar plot for age group.
- Bar plots for salary expenditure.
- Regression plot for age vs. salary correlation.

### 4. Key Insights

- The team with the **highest employee count** is highlighted.
- The most common **position** across all teams is noted.
- The **25–29 age group** dominates the employee distribution.
- One particular **team** and **position** account for the highest total salary expenditure.
- A **weak positive correlation** was observed between **age and salary** — indicating older employees generally earn more, though not always significantly.

## Technologies Used

- `Python`
- `Pandas`
- `NumPy`
- `Seaborn`
- `Matplotlib`
- `Jupyter Notebook`


## Repository Contents

| File | Description |
|------|-------------|
| `abc_company_analysis.ipynb` | The complete analysis with code, outputs, and visualizations |
| `abc co.csv` | The dataset used in this project |
| `README.md` | Project summary and instructions |

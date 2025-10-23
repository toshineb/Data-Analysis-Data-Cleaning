This repository showcases a collection of end-to-end **data cleaning, transformation, and exploratory data analysis projects** completed using **SQL, Python (Pandas, Seaborn, Matplotlib)**, and **Excel**.
The goal is to demonstrate practical data analytics skills from **raw data wrangling** to **insight generation** across multiple real-world datasets, including **movie industry profitability**, **COVID-19 statistics**, and **housing records**.

---

## 🧹 SQL Projects

### 🧩 **1. Data Cleaning – Nashville Housing Dataset**

**File:** `SQL - Data Cleaning.sql`
**Key Focus:**

* Standardized date formats and cleaned inconsistent address fields.
* Split multi-value address columns into **Address**, **City**, and **State** using SQL string functions and custom `SPLIT_STR()`.
* Normalized categorical data (`Y/N` → `Yes/No`) for clarity.
* Removed duplicate records using **CTEs** and `ROW_NUMBER()` windows.
* Dropped redundant columns to optimize database structure.

**Skills Demonstrated:**
`UPDATE`, `ALTER TABLE`, `CTE`, `JOINS`, `CASE WHEN`, `Window Functions`, `Data Normalization`

---

### 🌍 **2. Data Exploration – Global COVID-19 Dataset**

**File:** `SQL - Data Exploration.sql`
**Key Focus:**

* Analyzed pandemic trends across continents and countries.
* Calculated key health metrics: infection rate, mortality percentage, and vaccination coverage.
* Built **CTEs**, **Temp Tables**, and **Views** to streamline complex queries.
* Created rolling aggregates for vaccination tracking using window functions.

**Skills Demonstrated:**
`JOIN`, `GROUP BY`, `CTE`, `WINDOW FUNCTIONS`, `AGGREGATES`, `VIEWS`, `DATA TYPE CONVERSION`

---

## 🐍 Python Project

### 🎥 **3. Movie Industry Exploratory Data Analysis (EDA)**

**Files:**

* `Python - Movie Industry EDA Project.ipynb`
* `Python - Movie Industry EDA Project.pdf`

**Objective:**
Investigate the film industry to understand what drives profitability and develop data-driven recommendations for new entrants.

**Highlights:**

* Cleaned and merged multiple datasets (IMDb, theaters, actors, studios).
* Calculated inflation-adjusted budgets and profits.
* Explored **genre profitability**, **release timing**, **actor/director value**, and **Oscar success drivers**.
* Used **seaborn visualizations** to uncover trends such as:

  * Summer releases deliver higher profits.
  * Animation and Sci-Fi genres outperform others.
  * Top actors (e.g., Robert Downey Jr., Emma Watson) and directors (e.g., James Cameron) consistently exceed industry returns.

**Key Techniques:**
`pandas`, `numpy`, `seaborn`, `matplotlib`, `datetime`, `data cleaning`, `correlation analysis`, `visual storytelling`

---

## 📊 Excel Models

### 📈 **4. Excel Dashboards and Data Models**

**Files:**

* `Excel - LOOKUP, INDEX, MATCH, SUMIFS.xlsx`
* `Excel - Pivot Tables, Pivot Chart, Slicers.xlsx`
* `Excel - Scenario Manager, Solver (Data Modeling).xlsx`

**Highlights:**

* Built dynamic dashboards with **Pivot Tables**, **Charts**, and **Slicers** for interactive reporting.
* Used **Scenario Manager** and **Solver** to perform “what-if” analysis and optimize business outcomes.
* Applied **INDEX-MATCH**, **VLOOKUP**, and **SUMIFS** for advanced referencing and conditional calculations.

---

## 📂 Repository Structure

```
├── Python - Movie Industry EDA Project.ipynb
├── Python - Movie Industry EDA Project.pdf
├── SQL - Data Cleaning.sql
├── SQL - Data Exploration.sql
├── Excel - LOOKUP, INDEX, MATCH, SUMIFS.xlsx
├── Excel - Pivot Tables, Pivot Chart, Slicers.xlsx
├── Excel - Scenario Manager, Solver (Data Modeling).xlsx
└── README.md
```
Would you like me to generate a **GitHub-style cover image** (dark theme header banner showing Python, SQL, and Excel icons with “Data Analysis & Cleaning Portfolio” text) for this README? It would make your repo visually stand out.

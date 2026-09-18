
# Smartphone Usage Analysis — README

## 1. Project Overview

This project analyzes **smartphone usage and its effects on people's daily lives**.

The project uses three parts:

* **CSV dataset** – contains the smartphone usage records.
* **SQL file** – contains queries used to analyze the data.
* **Power BI report** – presents the analysis using charts, dashboards, filters, and KPIs.

The main purpose is to understand relationships between **screen time, smartphone addiction, sleep, stress, social media usage, gaming, and academic/work impact**.

---

# 2. Dataset — Smartphone_Usage.csv

The CSV dataset contains **7,500 records and 16 columns**.

The dataset includes information about:

### Personal information

* User ID
* Age
* Gender

### Smartphone usage

* Daily screen time
* Social media hours
* Gaming hours
* Weekend screen time
* Notifications per day
* App opens per day

### Daily activities

* Work/study hours
* Sleep hours

### Effects of smartphone usage

* Stress level
* Academic/work impact

### Addiction information

* Addiction level
* Addicted label

The `addicted_label` is represented as **0 or 1**, which can be used to identify whether a user is classified as addicted.

---

# 3. SQL Analysis

The SQL file is used to perform calculations and investigate patterns in the dataset.

### A. Average screen time and sleep

The SQL calculates the **average daily screen time** and **average sleep hours**. It also examines high-stress users. 

This helps answer questions such as:

> How much time do users spend on smartphones each day?

> How many hours do they sleep on average?

---

### B. Gender and addiction

The SQL groups users by **gender** and counts the number of users classified as addicted. 

This can be used to compare smartphone addiction patterns across genders.

---

### C. Missing data

The SQL checks whether important fields such as:

* Age
* Daily screen time
* Addiction level

contain missing values. 

This is useful for **data cleaning and quality checking** before analysis.

---

### D. Addiction and stress

The SQL groups the data by:

* `addicted_label`
* `stress_level`

and counts the users in each combination. 

This allows the project to investigate whether smartphone addiction classifications occur alongside different stress levels.

---

### E. Addiction level analysis

The SQL calculates the number of users and average:

* Screen time
* Sleep hours

for each addiction level. 

This is useful for comparing users at different addiction levels.

---

### F. Academic/work impact

The SQL compares academic/work impact with:

* Daily screen time
* Social media hours
* Gaming hours. 

This helps investigate how different types of smartphone usage relate to reported academic or work impact.

---

# 4. Power BI Dashboard

The Power BI file converts the data and SQL analysis into **visual reports**.

The report contains multiple pages, including:

* **Report1**
* **Report2**
* **Dashboard**
* **Dashboard2**
* **Dashboard3**

The reports use different visualizations such as:

* Bar charts
* Column charts
* Line charts
* Donut/pie charts
* Scatter charts
* KPI cards
* Slicers
* Decomposition tree
* Key-driver analysis

### Why Power BI is used

Instead of looking at thousands of rows in a CSV file, Power BI allows the user to **see patterns visually**.

For example, users can examine:

**Smartphone usage → Addiction → Stress/Sleep → Academic or Work Impact**

---

# 5. Main Topics of the Project

The project can be explained using these three major topics:

### Topic 1 — Smartphone Usage

This focuses on how people use their smartphones.

Important measurements include:

* Daily screen time
* Social media usage
* Gaming hours
* App opens
* Notifications
* Weekend screen time

---

### Topic 2 — Smartphone Addiction

This focuses on identifying different levels of smartphone addiction.

The dataset contains an **addiction level** and an **addicted label**.

The SQL analysis compares addiction with factors such as:

* Screen time
* Sleep
* Stress
* Gender

---

### Topic 3 — Effects of Smartphone Usage

This focuses on the possible effects associated with smartphone usage.

The project examines:

* Sleep hours
* Stress level
* Academic/work impact

The SQL specifically analyzes academic/work impact against screen time, social media usage, and gaming hours. 

---

# 6. Project Workflow

The complete project can be understood as:

**CSV Data**
↓
**Data Cleaning / Checking**
↓
**SQL Queries**
↓
**Data Analysis**
↓
**Power BI Visualizations**
↓
**Dashboard & Insights**

---

## 7. Project Objective

The main objective is to use data analysis and visualization to understand **smartphone usage patterns and their relationship with addiction, stress, sleep, and academic/work impact**.

This makes the project suitable for demonstrating:

* **SQL**
* **Data analysis**
* **Data cleaning**
* **Power BI**
* **Data visualization**
* **Exploratory analysis**

If you're preparing this for a **college project/seminar**, I can next make a **proper README with Abstract, Objectives, Technologies Used, Dataset Description, Methodology, Results, Conclusion, and Future Scope** in a format you can directly submit.

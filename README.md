# Excel Project 2 — Data Analytics Job Market & Salary Analysis

## 📊 Project Overview

This project analyzes the relationship between **technical skills, job roles, skill requirements, and salaries** in the data and analytics job market using Microsoft Excel.

The analysis was designed to identify which technical skills are most frequently required, how many skills are typically associated with different data-related job roles, and how median salaries vary across job positions, countries, and individual skills.

The project uses **PivotTables, calculated fields, and interactive visualizations** to transform job-market data into concise and actionable insights.

## 🎯 Objectives

The main objectives of this project are to:

* Identify the most frequently demanded technical skills in data-related jobs.
* Compare the number of skills required across different job roles.
* Examine the relationship between the number of skills required and median salary.
* Compare median salaries across different job roles and countries.
* Determine which technical skills are associated with higher median salaries.
* Build an Excel-based analytical dashboard for presenting the findings clearly.

## 🛠️ Tools & Techniques

* **Microsoft Excel**
* PivotTables
* PowerQuery
* PowerPivot
* PivotCharts
* Data aggregation
* Median salary analysis
* Skill-frequency analysis
* Comparative analysis
* Data visualization
* Dashboard development

## 📁 Workbook Structure

The workbook contains four analytical sheets:

### 1. `Skill_Job_Analysis`

Analyzes the frequency of technical skills appearing across job postings.

<img width="1322" height="382" alt="Skill_job_analysis" src="https://github.com/user-attachments/assets/9889b6e2-0aee-467c-a2bd-ccf8b624b912" />

**Key finding:** SQL and Python are the most frequently occurring skills in the analyzed job postings, indicating their strong demand across data-related roles.

### 2. `Skills_per_job`

Examines the average number of skills associated with different job titles and compares this with median salary.


<img width="1708" height="380" alt="Skills_per_job" src="https://github.com/user-attachments/assets/609234f4-73ea-4148-a98c-aefd727f2a1e" />

A scatter chart is used to explore whether jobs requiring a greater number of technical skills tend to have higher median salaries.

### 3. `Median_salaries_across_country`

Compares median salaries for different job roles, including separate salary measures for **US and non-US positions**.

The analysis allows comparison of how compensation varies geographically for roles such as:

* Senior Data Scientist
* Senior Data Engineer
* Data Scientist
* Data Engineer
* Senior Data Analyst
* Machine Learning Engineer
* Software Engineer
* Data Analyst
* Cloud Engineer
* Business Analyst

<img width="1232" height="496" alt="Median_salary_countries" src="https://github.com/user-attachments/assets/a7ecdc4f-fded-4ab7-a7c2-ef748b9030fa" />

The overall median salary in the analyzed dataset is **$115,000**, compared with **$118,940 for US positions** and **$111,175 for non-US positions**.

### 4. `Median_salary_skills`

Examines the median salary associated with individual technical skills while also showing the frequency of each skill.

<img width="1632" height="410" alt="Median_salary_skills" src="https://github.com/user-attachments/assets/fc4a382d-0d38-41ab-abb2-4390d3c785a3" />

A bar chart highlights the salary differences among the top 10 analyzed skills.

## 📈 Key Insights

### 1. SQL and Python dominate skill demand

SQL appears in approximately **18,500** job-skill records, while Python appears in **17,689**. These are substantially higher than the other analyzed skills, highlighting the importance of database querying and programming capabilities in the data job market.

### 2. Senior roles generally require broader skill sets

Senior Data Engineers have the highest average number of skills per job at approximately **8.33**, followed by Data Engineers at **7.22**. This suggests that engineering-oriented positions, particularly at senior levels, tend to require broader technical skill portfolios.

### 3. Higher skill requirements can coincide with higher salaries

The analysis indicates a general positive pattern between the number of skills associated with a job and its median salary. However, the relationship is not perfectly linear, meaning that the number of skills alone does not determine compensation.

### 4. Specialized technical skills command high salaries

Among the analyzed skills, **Spark ($140,000)** and **AWS ($135,000)** have the highest median salaries, followed by **Java ($134,241)**, **Azure ($125,000)**, and **Python ($125,000)**.

### 5. High-demand skills are not necessarily the highest-paid skills

SQL and Python have the highest skill counts, but Spark and AWS have higher median salaries. This demonstrates an important distinction between **skill demand/frequency** and **salary premium**.

### 6. Geographic differences exist

The salary analysis shows differences between US and non-US positions. For example, Machine Learning Engineer positions have a median salary of **$150,000 in the US compared with $101,029 outside the US**, illustrating the substantial geographic variation that can exist for the same job category.

## 📊 Dashboard & Visualizations

The workbook includes visualizations designed to communicate the analysis efficiently:

* **Top technical skills by job-skill frequency**
* **Skills per job vs. median salary**
* **Median salary by technical skill**
* **Job-role salary comparisons**
* **US vs. non-US salary comparisons**

These visualizations transform aggregated job-market data into an accessible dashboard suitable for exploratory analysis and presentation.

## 🔍 Business Questions Addressed

This project answers several practical questions:

1. **What technical skills are most demanded in data-related jobs?**
2. **Which job roles require the broadest range of technical skills?**
3. **Do jobs requiring more skills tend to offer higher salaries?**
4. **Which data-related job roles have the highest median salaries?**
5. **Which technical skills are associated with the highest median salaries?**
6. **How does compensation differ between US and non-US positions?**
7. **Does high skill demand necessarily translate into higher compensation?**

## 💡 Conclusion

The analysis demonstrates that the data and analytics job market places particularly strong emphasis on **SQL and Python**, while specialized technologies such as **Spark and cloud platforms such as AWS** are associated with comparatively high median salaries.

The results also suggest that senior and engineering-oriented positions tend to require broader technical skill sets and generally offer higher compensation. However, salary is influenced by multiple factors, including job role, geographic location, seniority, and the specific technical skills involved.

Overall, this project demonstrates how **Microsoft Excel can be used to perform structured job-market analysis, identify patterns in skill demand, compare compensation, and communicate insights through an interactive dashboard.**

## 📂 Project Files

* `Excel_Project_2.xlsx` — Complete Excel workbook containing the analysis, PivotTables, and visualizations.
* `README.md` — Project documentation and analytical summary.

## 👤 Project Type

**Data Analytics | Microsoft Excel | Job Market Analysis | Salary Analysis | Dashboard**

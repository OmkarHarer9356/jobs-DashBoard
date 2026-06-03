# 📊 Data Jobs Dashboard – Power BI Project (2 Reports)

> **A unified analytics project for data job seekers, featuring two distinct Power BI reports.**

This project tackles the fragmented nature of job market data by offering two complementary Power BI dashboards, built from the same dataset of 2024 data science job postings. While each report focuses on different analytical goals, together they provide a well-rounded view of trends, salaries, job roles, and skill demands.

---

## 🚀 Introduction

The modern data job market can be overwhelming—filled with inconsistent insights scattered across job platforms. This project consolidates and visualizes job market data using Power BI, giving **Job Seekers, Career Switchers, and Hiring Analysts** a clearer picture.

We use a single dataset of real 2024 data job postings (including titles, salaries, job types, skills, locations), and deliver two different reports within the same project, each tailored for a specific type of exploration:

- **📘 Report 1: Multi-Page Deep-Dive Report** – Focused on both market-wide overview and job-title-specific drill-through.
- **📗 Report 2: Single-Page Executive Summary** – Focused on quick, high-level insights ideal for fast exploration.

---

## 📁 Dashboard Files

- [`Data_Jobs_Dashboard.pbix`](Data_Jobs_Dashboard.pbix) – Report 1 (Two Pages)
  

---


## 📊 Report 1: Multi-Page Market Deep Dive

### 🧭 Overview

This two-page dashboard provides both a **broad market view** and a **deep-dive analysis** for individual job titles. It’s ideal for job seekers and analysts looking for a thorough breakdown of trends, salaries, and job characteristics.

---

### ✅ Page 1: High-Level Market Overview

This page offers a complete summary of the data job market at a glance, showing key KPIs and job trends over time.

![Dashboard Page 1](/Resources/images/Project1_Dashboard_Page1.gif)

**Insights Provided:**

- **🔢 Job Count**: Total number of job postings analyzed (~479K).
- **⭐ Avg. Job Rating**: A visual average rating based on available review data.
- **💰 Median Yearly & Hourly Salary**: At-a-glance compensation benchmarks.
- **📈 Jobs Over Time (Line Chart)**: Monthly trends showing rises and dips in job demand across 2024.
- **📊 Job Title Popularity (Bar Chart)**: Ranks the most frequently posted roles.
- **⚖️ Hourly vs Median Salary (Scatter Plot)**: Compares roles by both pay models, highlighting value gaps.
- **🧾 Job Stats Table**: Interactive table showing job title, job count, median salary (yearly/hourly), and job trend lines.

---

### 🔍 Page 2: Job Title Drill Through

Drill into this page from Page 1 to get **granular information** about a specific job title (e.g., Data Analyst).

![Dashboard Page 2](Resources/images/Project1_Dashboard_Page2.gif)

**Insights Provided:**

- **🎯 Salary Gauges**: Displays min, median, and max values for both yearly and hourly pay.
- **🏠 Work From Home %**: Percentage of roles mentioning remote/hybrid work.
- **🎓 No Degree Mention %**: Tracks jobs not requiring a degree—useful for non-traditional applicants.
- **❤️ Health Insurance Mention %**: Shows how many postings mention health benefits.
- **🌍 Global Job Distribution (Map)**: View of where jobs are concentrated worldwide.
- **🔎 Job Platform (Bar Chart)**: Shows distribution of postings by platform (LinkedIn, Indeed, BeBee, etc.).
- **📆 Job Schedule Type (Treemap)**: Reveals job types (full-time, contractor, internship, etc.) for the selected role.

---

### 🎥 Preview (GIF)

![Project 1 GIF](/Resources/images/Project1_Dashboard_Overview.gif)

---

### 🛠️ Key Features Used

- Power Query ETL
- DAX Measures (Median Salary, Job Count, etc.)
- Interactive visuals: slicers, buttons, bookmarks
- Drill-through navigation
- Map visuals, bar/line/area charts, KPI cards

---

## ⚡ Report 2: Single-Page Executive Dashboard (Version 2.0)

### 🧭 Overview

This streamlined, one-page dashboard presents the most **critical job market KPIs** and comparisons at a glance. It's ideal for quick insights without losing analytical depth.

![Dashboard Page 3](/Resources/images/Project2_Dashboard_Page1.png)

**Insights Provided:**

- **🔢 Job Count**: Total number of job listings (~479K).
- **📌 Skills Per Job**: Average number of skills required per job (approx. 4.8), providing a sense of role complexity.
- **💰 Median Salary (Yearly & Hourly)**: Market-wide compensation benchmarks.
- **📊 Skill Popularity (Bar Chart)**:
  - Displays top skills by job posting percentage (e.g., Python, SQL).
  - Toggle between **percent** and **count** to view by scale or frequency.
- **💼 Job Salary Comparison (Bar Chart)**:
  - Compares median yearly salary across different roles like Data Scientist, Cloud Engineer, and Software Engineer.
- **🎛️ Filters/Slicers**: Select **Job Title** and **Country** to customize the entire page.
- **🧭 Navigation Buttons**: Allow toggling between skill metrics and salary modes for flexible exploration.

This page is perfect for users who want high-level insights quickly—great for career planners, HR analysts, or executive viewers.

---

### 🎥 Preview (GIF)

![Project 2 GIF](/Resources/images/Project2_Dashboard_Overview.gif)

---

### 🛠️ Key Features Used

- One-page layout optimized for speed
- Star schema-based data model
- Slicers for interactive filtering
- Skill Popularity charts by count & percentage
- Salary comparison visuals across job titles

---

## 💡 Why This Project?

These two reports are intentionally different but complementary:

- Use **Report 1** when you need detailed analysis and context.
- Use **Report 2** when you want quick, executive-level answers.

Together, they help make the 2024 data job market more understandable and actionable for anyone navigating it.

---

## 🧠 Skills Demonstrated

- Data transformation using Power Query
- Efficient data modeling with relationships
- Advanced DAX calculations
- Visual storytelling with diverse chart types
- UX design for both deep and light exploration

---

## 📎 Included Files

- `Data_Jobs_Dashboard.pbix` – Full deep-dive dashboard  
- `Data_Jobs_Dashboard_2.0.pbix` – Single-page summary dashboard  
- `README.md` – Project documentation (this file)

---


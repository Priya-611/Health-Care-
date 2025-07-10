# Health Care Dashboard in Excel

An interactive Excel dashboard built using a healthcare dataset to help analyze patient demographics, hospital performance, treatment costs, and other critical healthcare indicators. The dashboard is designed for healthcare professionals, analysts, and decision-makers to gain quick insights and improve operational efficiency.

---

## Dataset Source

**Dataset Name:** [Healthcare Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)  
**Author:** Prasad Patil  
**Source:** Kaggle

The dataset includes information such as:
- Patient ID
- Age
- Gender
- Admission/Discharge dates
- Diagnosis
- Hospital charges
- Length of stay
- Department details

---

## Dashboard Features

- Total number of patient records with monthly trends
- Overall billing revenue and department-wise distribution
- Admission types breakdown (Emergency, Urgent, Elective)
- Top insurance providers by billing contribution
- Monthly and demographic patterns in admissions and diagnostics
- Interactive slicers for filtering (e.g., Gender, Department, Month)

---

## Project Workflow

1. Download and clean the dataset in Excel
2. Perform data preprocessing (remove blanks, correct data types, format dates)
3. Create pivot tables for key metrics (charges, length of stay, etc.)
4. Design visualizations using charts (column, pie, line charts)
5. Add slicers for interactivity (filter by gender, department, diagnosis)
6. Format the dashboard layout (titles, colors, borders for readability)
7. Finalize and test the dashboard for usability


---


## Key Performance Indicators (KPIs)

1. **Total Number of Patients**
   - Description: Total count of individual patient admission records.
   - Value: 40,235
   - Visualization:
     - KPI Card
     - Column Chart (Monthly & Yearly Trends)

2. **Total Billing Revenue**
   - Description: Sum of all billed amounts across patient services.
   - Value: ₹1.03 Billion
   - Visualization:
     - Column Chart (Month-wise)
     - Pie Chart (Department-wise)

3. **Admissions by Type (%)**
   - Description: Distribution of admissions by type: Emergency, Urgent, Elective.
   - Breakdown:
     - Emergency: 42%
     - Urgent: 38%
     - Elective: 20%
   - Visualization:
     - Pie Chart (Overall Distribution)
     - Stacked Column Chart (Trends Over Time)


---


## Analytical Objectives

1. **Top Insurance Providers Based on Billing**
   - Description: Identify insurance companies contributing the highest billing amounts.
   - Requirement: Sum billing amounts grouped by insurance provider.
   - Insight: Top 5 providers account for over 70% of total revenue.
   - Visualization:
     - Horizontal Bar Chart
     - Sorted Pivot Table

2. **Average Billing by Admission Type**
   - Description: Compare average billing for Emergency, Urgent, and Elective cases.
   - Requirement: Group and average billing by admission type.
   - Insight: Emergency cases had the highest average cost.
   - Visualization:
     - Bar Chart
     - Box Plot

3. **Growth Rate by Age Group**
   - Description: Track changes in patient inflow across age segments over time.
   - Requirement: Yearly comparison of admissions by age group.
   - Insight: Ages 36–55 showed consistent growth; seniors had seasonal peaks.
   - Visualization:
     - Line Chart (Segmented by Age Group)

4. **Monthly Trend of Admissions (Last 2 Years)**
   - Description: Observe seasonal patterns in admissions over time.
   - Requirement: Extract and visualize monthly admissions over 24 months.
   - Insight: Monsoon and winter months had higher admissions; March and October were typically low.
   - Visualization:
     - Area Graph
     - Heatmap

5. **Admission Type Distribution**
   - Description: Understand how frequent each admission type is.
   - Requirement: Count records by Emergency, Urgent, Elective.
   - Insight: Emergency and Urgent cases dominate; Elective is stable.
   - Visualization:
     - Pie Chart
     - Bar Plot

6. **Patient Test Result Trends**
   - Description: Analyze diagnostic outcomes across demographics.
   - Requirement: Categorize results as Normal, Abnormal, or Inconclusive.
   - Insight: Abnormal results common in older patients; inconclusive mostly from rapid tests.
   - Visualization:
     - Stacked Bar Chart
     - Trend Line

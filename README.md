# HR Analysis (A Full Data Analysis Project)

 
<img width="1169" alt="HR KPIs" src="https://github.com/user-attachments/assets/e8f4b423-e074-43fc-a7ea-d67ac156bd64">


## Table of Contents
- [Introduction](#introduction)
- [Project Steps](#project-steps)
  - [1. Data Collection](#1-data-collection---)
  - [2. Data Cleaning by SQL](#2-data-cleaning-by-sql----)
       - [SQL Queries](#download-sql-queries-data-cleaning-sql-queriessql)
  - [3. Connecting Tableau to PostgreSQL as a data source](#3-connecting-tableau-to-postgresql-as-a-data-source)
  - [4. Visualize the Data by Tableau](#4-visualize-the-data-by-tableau)
       - [Dashboards as PDF](#download-as-pdf-people-analytics-dashboardpdf)
       - [Download Tableau Workbook](#download-and-open-the-tableau-workbook-file-on-your-own-tableau-hr-data-analysis-tableau-workbooktwbx)
 


## Introduction
In this project, I preprocessed an HR dataset and created three insightful Tableau dashboards to visualize the data. The objective was to clean and transform the raw data to make it suitable for analysis, and then present key insights in an interactive and user-friendly dashboard.

</br></br>


-----

# Project Steps


### 1. Data Collection :  <img src="https://www.kaggle.com/static/images/site-logo.png" alt="Kaggle" width="70" />
The dataset was sourced from [HR Dataset Kaggle](https://www.kaggle.com/datasets/rhuebner/human-resources-data-set/data). 

|   ALL FEATURES         |                        |                        |                            |
|------------------------|------------------------|------------------------|----------------------------|
| Employee_Name          | EmpID                  | MarriedID              | MaritalStatusID            |
| GenderID               | EmpStatusID            | DeptID                 | PerfScoreID                |
| FromDiversityJobFairID | Salary                 | Termd                  | PositionID                 |
| Position               | State                  | Zip                    | DOB                        |
| Sex                    | MaritalDesc            | CitizenDesc            | HispanicLatino             |
| RaceDesc               | DateofHire             | DateofTermination      | TermReason                 |
| EmploymentStatus       | Department             | ManagerName            | ManagerID                  |
| RecruitmentSource      | PerformanceScore       | EngagementSurvey       | EmpSatisfaction            |
| SpecialProjectsCount   | LastPerformanceReview_Date | DaysLateLast30    | Absences                   |

</br></br>

### 2. Data Cleaning by SQL : <img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Sql_data_base_with_logo.png" alt="SQL" width="70" />  <img src="https://download.logo.wine/logo/PostgreSQL/PostgreSQL-Logo.wine.png" alt="SQL" width="70" />

Data cleaning was performed to ensure the dataset was free from errors and inconsistencies. 
</br> The following steps were taken:

- Remove Duplicates
- Standardizing data
- Convert data types
- Check Missing/NULL Values

##### Overview of the SQL Database (PostgreSQL)
<p align="Left">
<img width="700" alt="Overview of the Database" src="https://github.com/user-attachments/assets/bdc78904-f8b9-4a53-9d90-cc8c95db6b47">
</p>


#### Download SQL queries: [../Data-Cleaning-SQL-Queries.sql](https://github.com/tarafard/people-data-analysis/blob/main/Data-Cleaning-SQL-Queries.sql)
</br></br>


### 3. Connecting Tableau to PostgreSQL as a data source
<p align="Left">
<img width="700" alt="Connect to Database" src="https://github.com/user-attachments/assets/cfb24e0c-b831-44ac-965f-b7f310df032f">
<img width="700" alt="Manage Tableau Connections" src="https://github.com/user-attachments/assets/f378f2f9-480e-4e3b-880a-9df6f9c2fd4e">
<img width="700" alt="Hyper File" src="https://github.com/user-attachments/assets/af67afda-5a49-4580-ba41-fcc9f0a3c28c">
</p>
</br></br>

### 4. Visualize the Data by Tableau

- #### Final Tableau Dashboards

##### Download as PDF: [../People-Analytics-Dashboard.pdf](https://github.com/tarafard/people-data-analysis/blob/main/People-Analytics-Dashboard.pdf)
<p align="Left">
  <img src="https://github.com/user-attachments/assets/1aef16d2-db0c-4e79-80cd-04896539e7ee" width="700"/>
  <img src="https://github.com/user-attachments/assets/84d2e1fa-5eb5-42b0-b5fb-7e70c5d5e256" width="700"/>
  <img src="https://github.com/user-attachments/assets/364f0a7b-cc05-4cd0-a507-507f660c196b" width="700"/>
</p>



- #### Download and Open the Tableau Workbook file on your own Tableau: [../HR-Data-Analysis-Tableau-Workbook.twbx](https://github.com/tarafard/people-data-analysis/blob/main/Data-Analysis-Tableau-Workbook.twbx)


<p align="Left">
<img width="219" alt="Screenshot 2024-06-02 at 01 23 40" src="https://github.com/user-attachments/assets/241b144d-931c-422c-9959-e144a725b487">

</p>
</br></br>

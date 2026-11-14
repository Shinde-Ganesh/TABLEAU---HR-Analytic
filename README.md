# TABLEAU---HR-Analytics

Tableau Dashboard from Raw Data for HR Analytics

An end-to-end interactive Human Resources Analytics Dashboard built in Tableau to monitor employee demographics, hiring trends, termination rates, performance metrics, and salary distribution across departments and locations.

**Project Overview**

This project provides HR leaders and business decision-makers with actionable insights into workforce dynamics. The dashboard enables users to evaluate key HR metrics, track retention and attrition patterns over time, analyze salary distributions, and inspect individual employee records in detail.

**Dashboard Screenshot**

<img width="1428" height="826" alt="image" src="https://github.com/user-attachments/assets/d4b24cfe-3265-4f47-a63f-566d299a2ba3" />




 
**Data Architecture & Calculated Fields**

The dashboard utilizes a synthetic dataset containing employee demographic, performance, and financial attributes. Key custom calculated fields developed in Tableau include:


* Active Employees (Total Active) 

* Terminated Employees (Total Terminated)

* Total Hired (Total Hired)

* Employee Age (Age)

* Age Bins (Age Groups)

* Tenure / Length of Hire (Length of Hire)

* Location Classification (Location)


**Dashboard Views**


**1. HR | Overview / Summary**

KPI BANs (Big Angry Numbers): Real-time count of Active Employees, Total Hired, and Total Terminated.

Hiring & Termination Trends: Line and area charts displaying employee headcount changes year-over-year.

Department Breakdown: Bar chart visualizing workforce distribution across business units.

Geographic Analysis: State map and city-level bubble metrics comparing HQ vs. Branch distribution.

Demographics: Breakdown of workforce by Gender, Education Level (High School, Bachelor, Master, PhD), and Age Groups.

Education vs. Performance Rating: Matrix visualization evaluating employee ratings against educational backgrounds.

Compensation Analysis:

Gender vs. Education Level: Line plot comparing average salaries.

Age vs. Salary: Scatter plot highlighting salary benchmarks across job titles and age brackets.



**2. HR | Details**
A granular record table featuring Employee ID, Full Name, Age, Education, Department, Job Title, Location (State/City), Salary, Employment Status (Hired vs. Terminated), and Tenure.

Multi-select quick filters for Employee ID, Full Name, Gender, Age Group, and Education Level.



**Interactive Features**

Cross-Filtering: Click any bar, map, or demographic section to dynamically filter the entire dashboard.

Collapsible Filter Menu: Toggle icon on the top right to access multi-variable global filters (Gender, Status, Location, Hire Year).

PDF & Image Export: One-click action buttons to export dashboard views as standalone documents.

Direct Navigation: Smooth navigation between Summary and Detail views.



**Tools & Technologies**

Business Intelligence: Tableau Desktop

Design & Theme: Dark Mode UI with custom hex highlights (#03c4a1 Teal for Active/Hired, #c52a87 Pink for Terminated)


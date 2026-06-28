# Deloitte-Data-Analytics-Job-Simulation
Data Analytics project using Tableau and Excel to analyze machine downtime and gender pay equality as part of Deloitte's Forage Job Simulation.

## Project Overview  

This repository contains my solution for the Deloitte Data Analytics Job Simulation offered through Forage.

In this project, I worked on two real-world business scenarios using **Tableau** and **Microsoft Excel**. The main objective was to analyze business data, create meaningful visualizations, and provide insights that could support better decision-making.

---

## Tools Used

* Tableau
* Microsoft Excel

---

## Dataset

The Tableau task uses a JSON telemetry dataset provided as part of the Deloitte Forage simulation.

The Excel task uses an employee equality dataset containing Factory, Job Role and Equality Score.

---

# Task 1 – Machine Downtime Analysis

## Business Problem

Daikibo Industries collected machine telemetry data from four factories. Every machine sends its health status every 10 minutes.

The company wanted to answer two questions:

* Which factory experienced the highest machine downtime?
* Which device type failed the most in that factory?

---

## What I Did

### Imported the Dataset

* Imported the JSON dataset into Tableau.
* Selected all schema levels to load the complete dataset correctly.

### Created a Calculated Field

Created a calculated field named **Unhealthy**.

* Assigned **10** when the machine status was **Unhealthy**.
* Assigned **0** when the machine status was **Healthy**.

Each unhealthy record represents **10 minutes of machine downtime**.

### Built Visualizations

Created two Tableau worksheets:

* **Down Time per Factory**
* **Down Time per Device Type**

### Built an Interactive Dashboard

Combined both worksheets into a dashboard.

Enabled **Use as Filter** so that selecting a factory automatically updates the device type chart.

This makes the dashboard interactive and easy to explore.

---

## Project Outcome

The dashboard helps identify:

* Factory with the highest downtime
* Device type with the highest downtime
* Areas where preventive maintenance can reduce machine failures

---

# Task 2 – Gender Pay Equality Analysis

## Business Problem

The company wanted to analyze gender pay equality across different factories and job roles.

The dataset contained:

* Factory
* Job Role
* Equality Score

---

## What I Did

Created a new column named **Equality Class**.

Using an Excel IF formula with the ABS function, I classified each employee into one of the following categories:

* Fair
* Unfair
* Highly Discriminative

Applied the formula to the entire dataset and verified the results.

---

## Project Outcome

The completed analysis makes it easier to identify job roles that may require further pay equality review.

---

# Skills Demonstrated

* Data Analysis
* Tableau Dashboard Development
* Interactive Dashboard Design
* Microsoft Excel
* Calculated Fields
* IF & ABS Formula
* JSON Data Handling
* Data Visualization
* Business Analysis
* Problem Solving

---

# Files Included

* Tableau Dashboard Workbook (.twbx)
* Machine Telemetry Dataset (.json)
* Dashboard Screenshots
* Gender Pay Equality Excel File
* Deloitte Forage Completion Certificate

---

# What I Learned

This project helped me understand how organizations use data analytics to solve business problems.

I gained hands-on experience in Tableau dashboard development, Excel-based data analysis, and presenting insights through clear visualizations.

---

## Certificate

Successfully completed the **Deloitte Data Analytics Job Simulation** offered through **Forage**.

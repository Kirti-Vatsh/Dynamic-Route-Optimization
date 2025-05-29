# Rudi's Bakery Dynamic Route Optimization

A data-driven project optimizing delivery routes for Rudi's Bakery using advanced modeling, clustering, and optimization techniques. This project combines Python, Gurobi, and Google Maps API to create efficient delivery schedules that minimize travel time, maximize service points, and improve overall delivery efficiency.

# Problem Statement

Rudi's Bakery, a leading gluten-free and organic bread company, faced challenges with outdated delivery routes. The existing system led to increased delivery times, excessive labor, and inefficiencies, limiting customer service potential.

The goal of this project is to:

* Optimize two delivery routes starting from Colorado Springs.
* Service 53 stores across five days (Monday, Tuesday, Thursday, Friday, Sunday).
* Ensure Costco is serviced daily, and other stores at least 3 times a week.
* Reduce total delivery time and maintain 9-hour shift limits.

# Project Highlights

## Cleaned and verified data for 53 stores, adding ZIP codes and integrating Google Maps API for accurate time matrices.

* Clustered stores geographically (Castle Rock, Pueblo) to simplify model complexity.
* Developed optimization models using Gurobi and Python, integrated in Google Colab.
* Modeled under multiple constraints, including:

## Service frequency requirements (Costco daily, others 3x per week)
* Shift duration (max 9 hours)
* No 3-consecutive-day deliveries for non-Costco stores
* Delivered optimal routing solutions reducing delivery time and balancing routes.

## 🧰 Tools & Technologies

| 📊 Data Handling  | 🧠 Optimization  | 🌎 APIs & Platforms  |
|------------------|----------------|---------------------|
| Google Sheets    | Gurobi         | Google Maps API     |
| Python (pandas)  | MIP Modeling   | Google Colab        |
| Excel            | Clustering     |                     |

## 📂 Files in This Repository

| File                                         | Description                                          |
|----------------------------------------------|------------------------------------------------------|
| `Route_755_Vehicle_Optimization.ipynb`      | Python notebook with optimization models            |
| `S24_004_Group_6_Project1_FinalReport.pdf`   | Final project report detailing methodology & results |
| `S24_004_Group_6_Project1_Agile_Report.pdf`  | Agile project report and workflow documentation     |
| `S24_004_Group_6_ClientPresentation.pptx`    | Client presentation slides                           |
| `Project plan.pdf`                           | Project Gantt chart and timeline                     |

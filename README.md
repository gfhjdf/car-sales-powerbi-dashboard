

# Car Sales Analytics Dashboard (Power BI)

## Project Overview

This project demonstrates the process of transforming **raw transactional data into an interactive analytical dashboard** using Power BI.

The dataset initially consisted of **one large flat table containing car sales records**. The goal of this project was to clean and structure the data, build a proper analytical model, and design a dashboard that helps explore pricing behavior, vehicle characteristics, and sales performance.

The final result is a **multi-page Power BI dashboard** that allows interactive analysis of the dataset and highlights key insights about how vehicles are priced relative to market value.

---

## Objectives

The main goals of this project were:

* Transform raw tabular data into a structured analytical model
* Identify meaningful **KPIs and insights** from raw data
* Practice **data modeling and DAX calculations**
* Build an **interactive Power BI dashboard**
* Design clear and informative **data visualizations**

---

## Dataset

The dataset contains historical car sales records with information such as:

* vehicle details (make, model, body type, transmission)
* vehicle characteristics (condition, odometer, color, interior)
* pricing information (selling price and market value – MMR)
* seller and geographic data
* transaction dates

Originally, the data came as **one single table**, which required cleaning and restructuring before analysis.

---

## Data Preparation

Before building the dashboard, the dataset was prepared in Power BI by:

* cleaning inconsistent or missing values
* **normalizing data types**
* creating calculated columns
* preparing the data for analytical modeling

A **calendar table** was also created to support time-based analysis.

---

## Data Modeling

The project uses a **star schema data model**.

Main components:

**Fact Table**

* car sales transactions

**Dimension Tables**

* date
* vehicle attributes
* seller
* geography

This structure improves query performance and enables flexible analytical exploration.

---

## Key KPIs

The dashboard focuses on several key performance indicators:

* Total Sales Revenue
* Total Cars Sold
* Average Selling Price
* Average Vehicle Condition
* Average Odometer Reading
* Price vs Market Value (MMR)

These metrics help evaluate how vehicles are priced relative to the market.

---

## Dashboard Pages

The report contains multiple analytical pages:

**Executive Overview**
High-level summary of sales performance and market trends.

**Price vs Market Analysis**
Explores how vehicle prices compare to the market benchmark (MMR).

**Vehicle Insights**
Analyzes vehicle characteristics such as body type, mileage, and condition.

**Seller & Geographic Performance**
Shows sales distribution by sellers and locations.

**Model Insights (Drill-through page)**
Provides detailed analysis for selected vehicle models.

---

## Analytical Features

The dashboard includes several advanced Power BI visuals:

* Key Influencers
* Decomposition Tree
* Scatter Plot analysis
* Treemap visualization
* Geographic maps
* Drill-through analysis

These features allow deeper exploration of the data and help explain pricing patterns.

---

## Skills Demonstrated

This project helped develop and practice the following skills:

* Data cleaning and preparation
* Data type normalization
* Data modeling (star schema)
* DAX calculations
* KPI design and analytical thinking
* Power BI dashboard design
* Interactive reporting and drill-through analysis

---

## Tools Used

* Power BI Desktop
* DAX
* Data modeling techniques
* Data visualization best practices

---

## Author

Created as a personal learning project focused on developing practical skills in **Power BI, data modeling, and analytical dashboard design**.

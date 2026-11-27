# 🏡 King County House Sales Analysis

A Power BI project exploring residential property sales in King County,
Washington, USA.

------------------------------------------------------------------------

## 📌 Project Overview

This project focuses on analyzing house sales data using **Microsoft
Power BI**. The dashboard presents key property metrics and interactive
visuals to explore how house features, waterfront status, and location
relate to sale prices.

The project uses the `kc_house_data.csv` dataset and the Power BI report
`housedata.pbix`.

<img width="960" height="539" alt="Screenshot 2026-11-27 111423" src="https://github.com/user-attachments/assets/e9e0edf7-6188-44f3-9c6b-096b6d0585f3" />


## 🎯 Project Objectives

-   Analyze house sale prices and property characteristics.
-   Compare average prices based on bedrooms and bathrooms.
-   Understand the distribution of waterfront and non-waterfront
    properties.
-   Explore property locations using geographic visuals.
-   Provide an interactive dashboard for easy data exploration.

## 📂 Dataset Information

  Description                           Details
  --------------- -----------------------------
  Dataset               King County House Sales
  Total Records                          21,613
  Total Columns                              21
  Date Range        May 2, 2014 -- May 27, 2015
  File Format                               CSV

### Important Columns

  Column           Description
  ---------------- -------------------------------------------------
  `id`             Unique property identifier
  `date`           Date of sale
  `price`          House sale price
  `bedrooms`       Number of bedrooms
  `bathrooms`      Number of bathrooms
  `sqft_living`    Living area in square feet
  `sqft_lot`       Lot area in square feet
  `floors`         Number of floors
  `waterfront`     Indicates whether the property has a waterfront
  `view`           Property view rating
  `condition`      Overall property condition
  `grade`          Construction and design grade
  `yr_built`       Year the house was built
  `yr_renovated`   Year of renovation
  `zipcode`        Property ZIP code
  `lat`, `long`    Geographic coordinates

## 🧹 Data Preparation

The dataset was imported into Power BI and prepared for analysis.

The preparation workflow includes:

-   Checking column names and data types.
-   Reviewing missing and duplicate records.
-   Ensuring numeric fields are suitable for analysis.
-   Preparing fields for charts, filters, and geographic visuals.

**Source file check:** The supplied CSV contains 21,613 rows and 21
columns, with no blank cells or fully duplicated rows.

## 📊 Dashboard Features

The dashboard includes the following key visuals and interactive
elements:

-   **Total Houses** -- displays the total number of property records.
-   **Average Price** -- shows the average house sale price.
-   **Average Bedrooms** -- displays the average number of bedrooms.
-   **Average Bathrooms** -- displays the average number of bathrooms.
-   **Average Price by Bedrooms** -- compares average sale prices across
    bedroom counts.
-   **Average Price by Bathrooms** -- compares average sale prices
    across bathroom counts.
-   **Waterfront Distribution** -- a donut chart comparing waterfront
    and non-waterfront properties.
-   **Living Area Slicer** -- allows users to filter properties based on
    living area.
-   **Price Band Map** -- displays property locations grouped by price
    bands.

## 🔍 Business Questions

1.  What is the total number of houses in the dataset?
2.  What is the average house sale price?
3.  How does the average price vary with the number of bedrooms?
4.  How does the average price vary with the number of bathrooms?
5.  What is the distribution of waterfront and non-waterfront houses?
6.  How are houses distributed across different locations and price
    bands?
7.  How does living area help users explore property prices?

## 🛠️ Tools & Technologies

-   **Microsoft Power BI Desktop** -- dashboard creation and
    visualization.
-   **Power Query** -- data import and transformation.
-   **DAX** -- calculations and measures.
-   **CSV** -- source dataset.

## 📁 Project Files

  File                  Description
  --------------------- ------------------------------
  `kc_house_data.csv`   Original house sales dataset
  `housedata.pbix`      Power BI dashboard file
  `README.md`           Project documentation

## 🚀 How to Use

1.  Download the project files.
2.  Open `housedata.pbix` in Power BI Desktop.
3.  If prompted, connect the report to `kc_house_data.csv`.
4.  Refresh the data if required.
5.  Explore the dashboard using its charts and slicers.

## 💡 Key Insights

The dashboard makes it easier to explore the relationship between house
prices and property features such as bedrooms, bathrooms, living area,
and waterfront status. The geographic visual also helps users examine
how properties are distributed across different price bands.

## 👩‍💻 Project Summary

This project demonstrates the use of Power BI for data cleaning,
transformation, analysis, and interactive dashboard development. It
converts raw housing data into meaningful visual information that
supports housing-market exploration.

------------------------------------------------------------------------


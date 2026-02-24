# Retail Sales Interactive Dashboard (Quarto + Plotly)

## Overview

This project develops an **interactive analytics dashboard** to explore retail store performance using sales transaction data.

The dashboard allows users to visually investigate patterns in:

* seasonal sales trends
* regional performance
* product category demand
* discount impact on profitability

The goal is to demonstrate how raw operational data can be transformed into a decision-support tool for business stakeholders.

---

## Dashboard Features

The dashboard contains multiple interactive visual components:

### Sales Performance

* Monthly sales and profit trends
* Top cities by revenue
* Category contribution to total sales

### Seasonal & Regional Insights

* Seasonal sales variation by region (interactive Plotly visualization)
* Seasonal category performance
* Heatmap of sales across category and region

### Profitability Analysis

* Discount vs quantity relationship
* Discount impact on profit margins
* Correlation analysis between discount, quantity, and margin
* 3D interactive plot: discount vs quantity vs profit margin

Users can hover, zoom, and filter the plots directly in the browser.

---

## Technologies Used

* **R**
* **Quarto**
* **tidyverse / dplyr**
* **ggplot2**
* **Plotly (interactive visualization)**
* **lubridate**

---

## Dataset

Retail transactions dataset containing:

* order dates and shipping dates
* product category
* customer segment
* region and city
* quantity sold
* discounts
* profit and sales

---

## How to Run

1. Install Quarto: https://quarto.org
2. Clone the repository
3. Render the dashboard:

```bash
quarto render Pacman.qmd
```

4. Open the generated HTML file in your browser.

---

## Skills Demonstrated

* Data cleaning and preprocessing
* Feature engineering (season extraction, profit margin calculation)
* Interactive visualization
* Business data analysis
* Dashboard development
* Analytical storytelling

---

## Why This Project Matters

Businesses rely on dashboards to make operational decisions such as pricing, promotions, and inventory planning.
This project shows the ability to convert raw sales data into an interactive decision-support dashboard rather than a static analysis.

---

## Note

“Pacman” is the team name used in the original university project submission.
This repository contains my implementation and analysis.

---

## Author

Vaishnavi Kulkarni
MS Data Science

# World Bank Population Data Visualization

## Project Overview
This project demonstrates **data visualization of population data** using the World Bank indicator [SP.POP.TOTL](https://data.worldbank.org/indicator/SP.POP.TOTL), which represents the **total population** of countries over time.  

We fetch data directly from the **World Bank API**, perform **basic data cleaning**, and create **bar charts** and **histograms** to visualize population distributions.  

---

## Features
- Fetch population data for all countries for a specific year via the World Bank API.
- Clean the dataset by handling missing or null values.
- Create visualizations to analyze:
  - Top 10 countries by population (bar chart)
  - Distribution of population across countries (histogram)
- Easy-to-run Python scripts using `pandas`, `matplotlib`, and `requests`.

---

## Dataset
- **Source:** [World Bank - Total Population](https://data.worldbank.org/indicator/SP.POP.TOTL)
- **Data Type:** Numeric population values by country
- **Year:** User-specified (e.g., 2023)
- **Format:** JSON from API, converted to DataFrame for analysis

---

## Installation
Make sure Python 3.x is installed. Install the required libraries:

```bash
pip install pandas matplotlib requests

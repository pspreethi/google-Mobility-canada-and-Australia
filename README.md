
# Google Mobility Data Analysis: Canada and Australia

This project explores and analyzes mobility trends in Canada and Australia from 2020 to 2022 using Google Mobility Reports. The analysis highlights changes in mobility across various categories, including parks, retail, recreation, workplaces, transit stations, residential areas, and more. The goal is to understand how mobility patterns were affected during the COVID-19 pandemic.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Key Features](#key-features)
3. [Data Sources](#data-sources)
4. [Methodology](#methodology)
5. [Insights](#insights)
6. [Usage](#usage)
7. [Requirements](#requirements)
8. [Results](#results)
9. [Authors](#authors)

---

## Introduction

Google Mobility Reports provide anonymized insights into mobility trends across different regions and categories. These trends help understand public responses to events like the COVID-19 pandemic. This project focuses on comparing mobility patterns in Canada and Australia to study similarities, differences, and the impact of various restrictions.

---

## Key Features

- **Comparative Analysis**: Mobility trends for Canada and Australia across multiple categories.
- **Trend Visualization**: Graphs and charts to illustrate patterns in mobility changes.
- **Correlation Analysis**: Understanding relationships between mobility categories within each country.
- **Pandemic Insights**: Observations on how lockdowns and restrictions shaped mobility trends.

---

## Data Sources

The analysis is based on publicly available **Google COVID-19 Community Mobility Reports** for Canada and Australia. These reports track mobility trends relative to a pre-pandemic baseline.

---

## Methodology

1. **Data Cleaning and Preprocessing**: 
   - Extracted relevant metrics for both countries.
   - Filtered data for 2020 to 2022.

2. **Visualization**:
   - Generated trend graphs for categories like parks, transit stations, and workplaces.

3. **Correlation Analysis**:
   - Identified positively and negatively correlated mobility trends for each country.

4. **Insights**:
   - Compared mobility patterns and highlighted unique trends for Canada and Australia.

---

## Insights

### Canada:
- **High Mobility**: Parks saw a significant increase in visitors during the pandemic.
- **Low Mobility**: Transit stations experienced the steepest drop in mobility.
- **Trends**: Retail and recreation mobility approached pre-pandemic levels by late 2021.

### Australia:
- **High Mobility**: Residential areas had the largest increase in mobility.
- **Low Mobility**: Transit stations mirrored Canada with consistently low levels.
- **Trends**: Grocery and pharmacy mobility steadily returned to baseline by 2021.

### Shared Insights:
- **Similar Initial Response**: Both countries exhibited a sharp initial decline in mobility across most categories.
- **Residential Increase**: Mobility in residential areas increased globally during lockdowns.

---

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/pspreethi/google-Mobility-canada-and-Australia/.git
   cd google-mobility-analysis
   ```

2. **Run the Notebook**:
   - Open the `Google_Mobility_Analysis.ipynb` notebook.
   - Ensure the dataset is in the working directory.

3. **Generate Visualizations**:
   - Run the notebook cells to process the data and create visualizations.

---

## Requirements

- Python 3.x
- Libraries: `pandas`, `matplotlib`, `numpy`, `seaborn`, `jupyter`

Install dependencies using:
```bash
pip install -r requirements.txt
```

---

## Results

The analysis provides:
- Visualizations for mobility trends by category.
- Correlation heatmaps for mobility relationships within each country.
- Key differences in how mobility evolved in Canada and Australia during the pandemic.

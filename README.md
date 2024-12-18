## Matplotlib
---
# Pymaceuticals Drug Study Analysis

## Table of Contents
- [Description](#description)
- [Data Files](#data-files)
- [Features](#features)
- [Installation](#installation)
- [Results](#results)

---

## Description

**Pymaceuticals Drug Study Analysis** is a Python-based project that analyzes the effects of various drug regimens on tumor growth in mice. Using data analysis and visualization, this project identifies trends, compares drug performance, and provides insights into the effectiveness of specific treatments.

The project uses **Matplotlib** for data visualization and **pandas** for data analysis, executed within a **Jupyter Notebook**.

---

## Data Files

The project includes the following datasets:

| File Name                | Description                                      |
|--------------------------|--------------------------------------------------|
| `Mouse_metadata.csv`     | Contains metadata on individual mice used in the study, including unique IDs, sex, age, and weight. |
| `Study_results.csv`      | Contains results of the drug study, including tumor size over time for each drug regimen. |
| `pymaceuticals.ipynb`    | Jupyter Notebook performing data analysis and visualizations. |

---

## Features

- **Data Cleaning**:
  - Merges `Mouse_metadata.csv` and `Study_results.csv`.
  - Removes duplicate and corrupted records.

- **Exploratory Data Analysis**:
  - Summarizes tumor growth data for each drug regimen.
  - Analyzes the number of mice tested under each drug.

- **Statistical Analysis**:
  - Calculates summary statistics such as mean, median, and standard deviation for tumor sizes.
  - Compares drug performance using box plots, line charts, and scatter plots.

- **Visualization**:
  - Creates clear visualizations to illustrate tumor size over time for different drugs.
  - Highlights outliers and trends in the data.

---

## Installation

1. **Prerequisites**:
   - Python 3.x
   - Required libraries (if any) listed in `requirements.txt`.

2. **Setup**:
   - Clone this repository or download the project files.
     
   - Install dependencies (if needed):
     ```bash
     pip install -r requirements.txt
     ```
---

## Results

### Key Insights:

1.	Tumor Growth:
   - Drug regimens such as Capomulin and Ramicane are more effective in reducing tumor size compared to other treatments.
2.	Mouse Weight vs. Tumor Size:
   - Tumor size correlates positively with mouse weight in certain regimens, as seen in scatter plot analyses.
3.	Drug Performance:
   - Visualizations like box plots highlight that Capomulin and Ramicane have the lowest variance and smallest final tumor sizes.
---


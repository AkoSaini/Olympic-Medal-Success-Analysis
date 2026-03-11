# Olympic Medal Analysis: Athletes and Medal Success at the 2021 Tokyo Olympics

## Overview
This project analyzes whether countries that sent more athletes to the 2021 Tokyo Olympics also won more medals. Using data from 79 countries, I combined Olympic athlete and medal data with GDP data to explore the relationship between team size and medal success.

The project uses data analysis and statistical inference methods, including correlation, linear regression, and bootstrap resampling, to measure the strength of the relationship and estimate uncertainty.

## Research Question
Do countries that send more athletes to the Olympics tend to win more medals?

## Dataset
The analysis uses three datasets:
- `Athletes.csv` — athlete participation by country
- `medals.csv` — medal counts by country
- `gdp.csv` — GDP data by country

These datasets were cleaned and merged to create a final analysis table for 79 countries.

## Methods
The project includes:
- Data cleaning and table joins
- Exploratory data analysis
- Scatter plot visualization
- Correlation analysis
- Linear regression
- Bootstrap resampling for confidence intervals

## Key Result
The analysis found a strong positive correlation between number of athletes sent and medals won:

- **Correlation (r) = 0.799**

This suggests that countries sending larger teams generally tended to win more medals.

A bootstrap confidence interval was also constructed, showing that the positive relationship remained consistent across repeated resamples.

## Tools Used
- Python
- Jupyter Notebook
- `datascience` package
- NumPy
- Basic statistical inference methods

## Files in This Repository
- `Final Project Lab - DAM II.ipynb` — main analysis notebook
- `Athletes.csv` — athlete dataset
- `medals.csv` — medal dataset
- `gdp.csv` — GDP dataset
- `DAM II FP Slides.pptx` — presentation slides

## How to Run
1. Clone or download this repository.
2. Make sure all CSV files are in the same folder as the notebook.
3. Open the notebook in Jupyter Notebook or JupyterLab.
4. Run all cells in order.

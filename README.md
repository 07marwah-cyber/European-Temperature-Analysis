# European Temperature Analysis

A statistical analysis of daily surface air temperature data from two European cities, conducted in R.

The project investigates differences in temperature between 1996 and 2011 and compares the climatic characteristics of the two cities using exploratory data analysis, visualisation and hypothesis testing.

## Project Overview

The dataset contains 731 daily observations across 1996 and 2011. The analysis examines whether temperatures changed between the two years and whether the two cities exhibit statistically different temperature patterns.

The main questions investigated were:

- Does the mean temperature of City X in 2011 differ from its historical reference mean?
- Did mean temperature increase between 1996 and 2011?
- Is the same pattern observed when considering August temperatures only?
- Do City X and City Y have significantly different mean temperatures during January and August 2011?

## Methods

The analysis was carried out using R and R Markdown.

Techniques used include:

- Data cleaning and validation
- Exploratory data analysis
- Time-series visualisation
- Histograms and box plots
- Summary statistics
- Confidence intervals
- One-sample t-tests
- Welch two-sample t-tests

## Key Findings

- City X showed statistical evidence of higher mean temperatures in 2011 compared with 1996.
- City Y showed no statistically significant increase over the same period.
- The August analysis produced a similar pattern, with evidence of an increase for City X but not City Y.
- City Y had significantly higher mean temperatures than City X in both January and August 2011.

These results suggest that the observed temperature change was not consistent across the two locations.

## Repository Structure

```text
European-Temperature-Analysis/
├── data/
│   └── Temperature_data.csv
├── Analysis.Rmd
├── Report.pdf
└── README.md

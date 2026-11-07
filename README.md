# Environmental Toxin Analysis in River Systems

## Project Overview

This project uses exploratory data analysis (EDA) to investigate toxin concentrations and water-quality measurements across five major river systems between 2018 and 2022.

The analysis was conducted for a fictional environmental non-profit, EcoGuard, to identify patterns in toxin concentrations, explore differences between river systems and investigate relationships between environmental measurements.

## Objectives

- Compare average toxin concentrations across five river systems.
- Investigate changes in toxin concentrations over time.
- Explore relationships between pH and toxin measurements.
- Examine seasonal variation in toxin concentrations.
- Apply statistical testing and linear regression.
- Communicate findings and recommendations based on the analysis.

## Tools and Technologies

- Python 3
- JupyterLab
- pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Methods

The project involved:

- Data inspection and quality assessment.
- Handling missing measurements.
- Descriptive statistics and group comparisons.
- Monthly time-series analysis.
- Correlation analysis and heatmap visualisation.
- Seasonal analysis using box plots.
- Welch independent-samples t-test.
- Simple linear regression.

## Key Findings

- The Yangtze had the highest average Lead, Mercury and Arsenic concentrations.
- The Nile had the highest average Nitrates concentration.
- The Amazon had the highest average Phosphates concentration.
- Spring recorded the highest average concentrations across all five toxins, while Autumn recorded the lowest.
- pH showed a positive relationship with Lead, but explained only 10.57% of its variation.
- Toxin concentrations fluctuated over the five-year period without a consistent overall upward or downward trend.

## Limitations

The dataset did not specify measurement units or regulatory thresholds, so the analysis cannot establish whether measurements exceeded environmental safety limits.

Seasonal classifications followed Northern Hemisphere conventions, which may not reflect local seasons for all river systems. Correlation and regression findings indicate associations rather than causation.

## Repository Structure

```text
Project_02_River_Toxin_Analysis_EDA/
├── data/
├── notebooks/
├── outputs/
└── README.md
```

## Project Deliverables

- Exploratory data analysis notebook.
- Visualisations of toxin concentrations and water-quality patterns.
- Final report prepared for EcoGuard.

## Conclusion

This project demonstrates the use of Python for environmental data analysis, statistical investigation and data visualisation. It highlights differences between river systems and identifies areas where further monitoring and investigation may be valuable.
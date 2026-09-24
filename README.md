# The Effect of Economic Freedom on the Equity-Efficiency Tradeoff

**A Causal Analysis**

Research paper by **Jonathan Barazzutti, Talha Fatir, and Prince Kafeke** examining how economic freedom relates to economic growth and income inequality across countries.

## Project Overview

This study investigates whether greater economic freedom creates an equity-efficiency tradeoff: higher economic growth at the cost of greater income inequality.

The analysis uses a balanced panel of **123 countries from 2000 to 2021** and combines fixed-effects regression, institutional-control sensitivity analysis, income-group comparisons, and panel Granger-causality testing.

## Research Questions

- Does greater economic freedom relate to higher GDP per capita?
- Does greater economic freedom affect income inequality?
- Do these relationships differ across specific components of economic freedom?
- Are the relationships different in higher-income and lower-income countries?
- Does economic freedom predict future economic growth, or does growth predict future economic freedom?

## Data Sources

The study combines:

- **Fraser Institute – Economic Freedom of the World 2023** for economic-freedom measures
- **Gapminder Foundation** for GDP per capita and Gini coefficient data
- **Global State of Democracy Indices** for institutional controls used in the sensitivity analysis

## Economic Freedom Measures

Ten measures are analyzed:

1. Overall Economic Freedom
2. Government Consumption
3. Size of Government
4. Property Rights
5. Legal System and Property Rights
6. Freedom to Trade Internationally
7. Labor Market Regulation
8. Business Regulation
9. Freedom to Compete
10. Overall Regulation

## Methodology

### Fixed-Effects Models

Country fixed-effects regressions are used to estimate relationships between economic freedom and:

- GDP per capita
- Gini coefficient

The fixed-effects framework controls for time-invariant country characteristics.

### Sensitivity Analysis

Institutional controls are added for:

- Representative Government
- Fundamental Rights
- Checks on Government
- Impartial Administration

The sample is also analyzed separately for higher-income and lower-income countries.

### Granger-Causality Analysis

Panel Granger non-causality tests are used to examine predictive direction between economic freedom and GDP per capita.

The study uses Stata's `xtgrangert` implementation and tests models with up to five time lags.

> Granger causality in this project refers to **predictive causality**: whether past values of one variable improve prediction of another. It should not be interpreted as definitive structural causality on its own.

## Key Findings

- Overall economic freedom is positively associated with economic growth.
- Overall economic freedom does not show a statistically significant relationship with inequality in the pooled sample.
- Results vary substantially across individual components of economic freedom.
- The relationship between economic freedom and growth is generally weaker in lower-income countries than in higher-income countries.
- Inequality effects differ across income groups and policy components.
- With four or five time lags, the Granger-causality analysis finds evidence of bidirectional predictive causality between economic freedom measures and economic growth wherever the relevant test statistic could be estimated.
- The results suggest that a broad equity-efficiency tradeoff is not consistently present across all forms of economic freedom or all country groups.

## Tools & Techniques

- Stata
- Panel-data econometrics
- Fixed-effects regression
- Robust standard errors
- Sensitivity analysis
- Granger-causality testing
- Cross-country panel-data analysis
- Microsoft Excel for data organization
- Academic literature review and research writing

## Paper

The full research paper is available here:

[**Read the full paper (PDF)**](paper/Economic-Freedom-Paper.pdf)

## Repository Structure

```text
economic-freedom-equity-efficiency/
├── README.md
└── paper/
    └── Economic-Freedom-Paper.pdf
```

## Authors

- Jonathan Barazzutti
- **Talha Fatir**
- Prince Kafeke

## Notes

This repository is intended as a research and portfolio archive. The paper's findings, interpretation, limitations, references, regression tables, and full methodology are contained in the PDF.

# Growth and Air Pollution: An Environmental Kuznets Curve (EKC) Perspective

Analysis of the relationship between economic growth (GDP per capita) and air pollution (CO₂ emissions per capita) across five countries, testing whether the Environmental Kuznets Curve (inverted-U) hypothesis holds consistently for developed vs. developing economies.

## Team

| ID | Name |
|---|---|
| ITBNM-2313-0039 | N.A.A. Shashini Kavindaya |
| ITBNM-2313-0049 | I.M. Kalani Mekhala |
| ITBNM-2313-0027 | M.K.K. Chamodika Gayathri |
| ITBNM-2313-0007 | M.M. Samadhi Dilshani |
| ITBNM-2313-0021 | D.M. Nalan Dissanayaka |

## Background

Economic growth is closely tied to energy consumption and environmental impact. The Environmental Kuznets Curve (EKC) hypothesis suggests pollution rises during early industrialization, then falls as income, technology, and policy improve — forming an inverted-U shape. Developed nations (e.g., Norway, Germany, Japan) show declining or stable emissions, while rapidly industrializing nations (e.g., China, India) show a rising trend, though some are approaching an inflection point through green-energy investment.

## Research Questions

- How has the relationship between GDP growth and CO₂ emissions evolved across selected countries over the past two to three decades?
- Does the EKC (inverted-U) pattern hold consistently for both developed and developing economies?
- What factors (technology, policy, energy mix) explain divergence from the expected EKC pattern?

## Objectives

- Collect 20–30 years of GDP and CO₂/air-pollution data for five selected countries
- Test the EKC hypothesis against the collected data
- Build comparative visualizations (Python: matplotlib/seaborn) of growth vs. pollution trends
- Draw evidence-based conclusions on sustainable development pathways

## Data Sources

All datasets are publicly available in CSV format:

- **Kaggle — World Development Indicators (WDI):** GDP and CO₂ emissions indicators for every country, filterable by country and year
- **Our World in Data — CO2 Emissions Dataset:** Global CO₂ emissions data from 1750 to present
- **World Bank Open Data — GDP & CO2 Datasets:** Official GDP per capita and CO₂ emissions series

## Repository Contents

- `EKC_Regression_Model.ipynb` — Data cleaning/preprocessing (missing values, duplicates/outliers, GDP² feature creation) and quadratic regression modeling of GDP vs. CO₂ emissions per country, plus comparative EKC visualizations
- Additional notebooks cover exploratory analysis: emissions trend lines (1995–2025), GDP-CO₂ scatter plots with regression fit, normalized growth trajectories, correlation heatmaps, and country-level (e.g., China) trajectory plots

## Methodology

- **Language/Libraries:** Python — pandas, numpy, matplotlib, seaborn
- **Modeling:** Second-degree polynomial (quadratic) regression fitted per country on GDP per capita vs. CO₂ emissions per capita, to test for the inverted-U EKC relationship
- **Data period:** ~1995–2025, five countries



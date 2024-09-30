# UK Employment Trends Analysis (1991-2023)

## Overview
This project analyzes UK employment trends from 1991 to 2023 using World Bank data. It explores gender dynamics in the labor force, part-time employment, self-employment, and correlations between key employment indicators.

## Data Source
- World Bank's World Economy Indicators
- Filtered for United Kingdom (GBR)
- Focus on employment-related indicators

## Data Preparation
1. Categorized 31 indicator types
2. Selected employment category
3. Removed irrelevant indicators and empty data
4. Converted "Year" column to appropriate data type
5. Transposed dataframe (years as index, indicators as columns)

## Analysis Highlights
- Female to male labor force participation ratio
- Part-time employment rates by gender
- Self-employment trends by gender
- Correlation analysis of key employment indicators

## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook

## Repository Structure
- `clean/`: Cleaned dataset
- `/`: Jupyter notebooks with analysis
- `media/`: Visualizations generated from the analysis
- `README.md`: Project overview (this file)


## Disclaimer
This analysis is based on processed World Bank data and should be interpreted cautiously. Limitations in data granularity and potential processing errors may affect the findings' precision and comprehensiveness.

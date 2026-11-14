# Argentina CO2 Emissions Analysis (1990–2024)

## Project Overview

This project examines Argentina's annual carbon dioxide (CO2) emissions from 1990 to 2024 using data from Our World in Data. The analysis focuses on total annual emissions, emissions per capita, and year-to-year percentage changes.

## Data and Methods

The source dataset is the Our World in Data CO2 emissions dataset. The analysis filters the data using Argentina's ISO-3 country code (ARG) and the years 1990–2024. Base R functions are used for data cleaning, calculations, visualization, and exporting results. The full source dataset is excluded from version control through .gitignore.

## Key Findings

Argentina's annual CO2 emissions increased from 112.79 million tonnes in 1990 to 178.96 million tonnes in 2024, representing an overall increase of 58.68%. Emissions reached their highest recorded level in this study period in 2015, at 190.77 million tonnes. The latest reported per-capita emissions were 3.92 tonnes per person in 2024.

Year-to-year changes were not consistently positive. Emissions decreased by 8.95% in 2020, increased by 15.84% in 2021, and then decreased by 5.20% in 2024. These results show that Argentina's emissions fluctuated over the study period despite the overall increase between the first and last years.

## Figures

![Annual CO2 emissions](figures/ARG_annual_co2.png)

![CO2 emissions per capita](figures/ARG_per_capita.png)

![Annual percentage change](figures/ARG_annual_change.png)

## Project Outputs

- `data/ARG_co2.csv`: filtered country dataset.
- `figures/`: three generated graphs.
- `results/ARG_summary.csv`: summary statistics.
- `results/ARG_yearly_changes.csv`: annual emissions and percentage changes.
- `results/session_info.txt`: R session information.
- `scripts/analyze_co2.R`: reproducible analysis script.

## Reproducibility

Open the RStudio project and run `source("scripts/analyze_co2.R")` in the Console. The script downloads the source dataset if it is not already available.

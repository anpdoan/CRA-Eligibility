# CRA-Eligibility
This respository contains the source codes in R and data for my Senior Capstone paper titled: "Analyzing the Community Reinvestment Act (CRA): A Catalyst for Small Business Lending? Evidence from the 2018 MSA Definition Change."

## Overview

The goal of this paper is to analyze the effect of tracts losing/gaining Community Reinvestment Act (CRA) eligibility following an exogenous policy shock, the 2018 Metropolitan Statistical Area (MSA) redefinition in the United States. The CRA is a federal law enacted to encourage depository institutions to meet the credit needs of the communities in which they operate, particularly low- and moderate-income (LMI) neighborhoods. CRA eligibility is determined when a census tract's median family income is below 80% of its respective MSA median family income. Because of the 2018 MSA redefiniton, many census tracts across US lose/gain CRA eligibility due to new values of baseline MSA median family income without necessarily getting better or worse financially. The exogenous policy shock is used as a natural experiment to investigate the efficacy of the CRA program regarding two treatment groups: Newly CRA-Eligible tracts and Newly CRA-Ineligible tracts using a Difference-in-Differences (DiD) model with fixed effects.

## Contents

- `data/`: This directory contains the datasets from FFIEC used in the paper.
- `scripts/`: This directory contains R scripts used for data preprocessing, analysis, and visualization.
- `paper/`: This directory contains the Senior Capstone paper.
- `LICENSE`: The license under which this project is distributed.

## Requirements
- R (version 3.5.0 or higher)
- R packages: tidyverse, ggplot2, dplyr, readxl, xtable, writexl, stargazer, foreign, ggthemes, cowplot, scales

## License
This project is licensed under the MIT License. Feel free to use the code and data for your own projects, but please provide appropriate attribution.

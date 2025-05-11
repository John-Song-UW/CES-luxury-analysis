# Analysis of luxury vs. general consumption dynamics during the COVID-19 economic shock using CES microdata (2019–2023).

This project analyzes how luxury vs. general consumer spending in the U.S. responded to the COVID-19 economic shock using Consumer Expenditure Survey (CES) microdata from 2019–2023.

## 📊 Methods

- Data: CES MTBI + FMLI (U.S. BLS public microdata)
- Classification: Luxury transactions defined by UCC + price thresholds
- Design: Difference-in-Differences (DID) model with pre-trend validation
- Tools: R, tidyverse, fixest, CPI adjustment, household-level weighting

## 🔍 Key Findings

- High-income households sharply reduced luxury spending during the 2020 shock, then rebounded to exceed pre-pandemic levels.
- General spending remained stable, while low-income luxury demand showed limited volatility.
- Luxury consumption is highly sensitive to economic uncertainty and should be analyzed separately from general trends.

## 📁 Repository Structure

- Data: CES-based input data (public-safe version)
- Codes: R scripts for merging, filtering, modeling
- Output: Figures, regression tables, and write-up
- CSSS_322_Final.pdf: Final report

## 👤 Author

John Song  
Undergraduate, University of Washington  
Course: CSSS 322 – Quantitative Research in the Social Science

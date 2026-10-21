# BDA400 Assignment 2 — Technical Analysis using R

Student: Stephenie Olorunmaiye  
Repository required by brief: `TechnicalAnalysis`

This folder contains a preliminary technical-analysis workflow. It reads stock symbols from `portfolio.txt`, downloads price data through `quantmod`, calculates statistics, prints data samples, and saves CSV summaries and PNG charts.

## Files
- `portfolio.txt` — one ticker symbol per line.
- `scripts/technical_analysis.R` — import, statistics, display, and plotting functions.
- `reports/Assignment2_Report_Draft.md` — report draft with screenshot placeholders.
- `AI_Use_Disclosure.md` — AI-use statement.

## Run
Set the working directory to this `Assignment2` folder (the folder containing `portfolio.txt`), then run:

```r
source("scripts/technical_analysis.R")
```

Required packages: `quantmod` and `TTR`. The script attempts to install them if missing. Live data retrieval requires internet access and a functioning Yahoo Finance connection.

Your earlier RStudio screenshot showed R 3.6.1, which is old. If packages fail to install, install a current R version from CRAN and restart RStudio.

**Important:** Run and verify the script yourself, inspect outputs, and add genuine screenshots to the report. Do not claim unperformed checks are complete. This is educational material, not investment advice.

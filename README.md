# NHANES Data Analysis & Visualization Assignment

## Project Overview
This repository contains the complete R Markdown file for exercise 2-4 from last week, code, datasets, exported figures, and rendered reports. The project utilizes the historical **NHANES** dataset (maintaining original naming conventions like `RIAGENDR` for biological sex and `RIDRETH1`/`RIDRETH3` for race) to explore age, gender, ethnicity distributions, longitudinal weight changes, and blood pressure relationships.

## Repository Structure
* `code/` - contains the source R Markdown (`.Rmd`) file.
* `data/` - Contains the cleaned CSV datasets (`cleaned_nhanes.csv`, `diet (1).csv`).
* `figs/` - Stores exported high-resolution visualization plots (`.png`).
* `reports/` - Contains the final rendered PDF report.

## Reproducibility & Navigation
All file paths are configured using relative paths via the `here` package. To view the final compiled work without running code from scratch, open the pre-rendered PDF document located in the `reports/` folder.
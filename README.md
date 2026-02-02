# Medicaid Expansion and SNAP Participation: Heterogeneous Effects

## Overview
This project examines how the Affordable Care Act’s Medicaid expansion affected participation in the Supplemental Nutrition Assistance Program (SNAP), with a focus on **heterogeneous effects across demographic groups**. While prior studies document a positive spillover from Medicaid to SNAP participation, they largely focus on average effects. This project studies whether those spillovers differ by **race, education, and gender**.

Evaluating these heterogeneous responses is important for understanding how Medicaid expansion affected SNAP participation, which populations drive the observed spillovers, and how the broader impacts of health policy are distributed.

## Main Findings
I find that Medicaid expansion increased SNAP participation **among non-white individuals**, with an estimated increase of approximately **3.6 percentage points**. This effect is concentrated among **Hispanic individuals**, who experience an increase of about **4.1 percentage points**. I find **no statistically meaningful effect for white individuals**. I find no economically meaningful differences by gender.

These patterns are robust when the analysis is re-estimated separately for **parents** and **non-parents**, suggesting that the observed heterogeneity is not driven solely by household composition.

## Data and Variable Construction
- Data come from the **Current Population Survey Annual Social and Economic Supplement (CPS ASEC)**.
- **SNAP participation** is defined as a binary indicator equal to 1 if an individual reports receiving SNAP benefits **in that year**, and 0 otherwise.
- Medicaid expansion status is defined at the state level following ACA implementation.

## Empirical Strategy
The analysis uses a **difference-in-differences** framework comparing Medicaid expansion states to non-expansion states before and after expansion. I estimate models for:
- The full sample
- Parents only
- Non-parents only

Heterogeneity is examined by race, education (high school completion) and gender.

## Code Structure
This repository contains both **Python** and **Stata** code. Files were uploaded manually (not via Git).

### Python (Jupyter Notebooks)
- Data cleaning and regression analysis replicating the main specifications
- Plots of raw mean SNAP participation over time using `matplotlib`

### Stata Do-Files
- Replication of all main regressions
- Event-study analyses

The Python and Stata files implement the **same empirical specifications**, allowing results to be verified across software environments.

## Figures
- **Raw mean trends** are plotted using Python (`matplotlib`)
- **Event-study plots** in the graphs folder produced using Stata

All figures correspond directly to the included code.

## Notes
This repository is intended for **transparency and replication**. File names are descriptive, and scripts are written to be read sequentially. Results shown in the figures and tables can be reproduced using either Python or Stata.


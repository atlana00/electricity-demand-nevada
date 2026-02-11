# Residential Electricity Demand in Nevada  
### Top-Down vs Bottom-Up Estimation Framework

This repository documents graduate-level research on residential electricity demand estimation in the State of Nevada using both aggregated (top-down) and household-level (bottom-up) approaches.

The purpose of this work is to illustrate how aggregation, geography, and data structure influence inferred price and income elasticities in energy demand models.

---

## Research Question

How does the estimation of residential electricity demand differ when modeled using:

- Aggregated utility-level data (top-down)
- Household-level microdata (bottom-up)

This project highlights how aggregation can materially alter inferred elasticities even when standard variables are used.

---

## Data Sources

- U.S. Census Bureau (ACS PUMS)
- U.S. Energy Information Administration (EIA)
- National Climatic Data Center (NCDC)
- Nevada utility service territories

No proprietary or raw microdata are included in this repository.

---

## Methodology Overview

Two log-log models are estimated:

### Top-Down Model
Per-capita electricity consumption as a function of:
- Electricity price
- Natural gas price
- Income
- Heating and cooling degree days

### Bottom-Up Model
Household electricity consumption as a function of:
- Electricity price
- Natural gas price
- Income
- Household size
- Dwelling size
- Ownership status
- Climate variables

Both models are estimated using Ordinary Least Squares (OLS) with diagnostic testing for heteroscedasticity, multicollinearity, and specification.

---

## Key Insight

Top-down and bottom-up models do not estimate the same behavioral object.  
Aggregation changes the estimand.

This repository preserves the modeling framework and empirical results for transparency and discussion.

---

## License

Shared for academic and educational purposes.

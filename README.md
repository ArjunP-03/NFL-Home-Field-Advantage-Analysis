# NFL Home-Field Advantage Analysis

## Overview

This project investigates whether NFL home-field advantage has decreased since the COVID-19 pandemic. Using NFL game data from 2010–Present, I compare home-team performance before and after the pandemic.

## Research Question

**Has NFL home-field advantage decreased since the COVID-19 pandemic?**

## Methodology

The analysis compares two periods:

* **Pre-COVID:** 2010–2019
* **Post-COVID:** 2021–2025
* **2020:** Excluded due to unusual game and attendance conditions during the pandemic.

Home-field advantage was evaluated using:

* Home-team win percentage per season(Visual)
* Home-team win percentage split by era(2010-2019 and 2021-Present)
* Two-proportion z-test to determine whether the change in home-team win percentage was statistically significant

## Results

Home-team win percentage decreased from **56.70%** in the pre-COVID period to **54.46%** in the post-COVID period, a decrease of **2.24 percentage points**.

A two-proportion z-test produced a **p-value of 0.1675**, which is greater than the 0.05 significance level. Therefore, the observed decrease was **not statistically significant**.

### Conclusion

Although home-team win percentage decreased after COVID-19, there is not sufficient statistical evidence to conclude that NFL home-field advantage decreased.

## Tools

* Python
* Pandas
* NumPy
* Matplotlib
* Statsmodels
* Jupyter Notebook

# Population Growth Forecasting in Penang

## Overview
Population growth is an important factor in planning for food, water, infrastructure, and other public resources. This project applies mathematical and computational methods to analyze and forecast population growth in Penang, Malaysia.

## Objective
The objectives of this project are to:
- Evaluate the predictive accuracy of multistep methods for solving a logistic population growth model.
- Forecast the population of Penang up to the year 2030 using the Adams-Bashforth-Moulton (ABM4) method.

## Methodology
The analysis uses population data for Penang from 2015 to 2025 and applies a logistic population growth model. 

The numerical methods  considered include:
- Fourth-order Runge-Kutta (RK4) method
- Fourth-order Adams-Bashforth-Moulton (ABM4) method
- Milne-Simpson method

The ABM4 method is further evaluated using different values of the carrying capacity parameter, and its performance is compared with Milne's method.

## Results
The results show that:
- The multistep methods  achieved a minimum error of approximately **0.27%**.
- ABM4 demonstrated suitable predictive performance and was selected for population forecasting.
- The population trend during 2018-2022 showed a stagnation that differed from the idealized logistic model, reflecting the impact of the COVID-19 period.
- Using the ABM4 method, the population of Penang was forecast up to **2030**.

## Conclusion
The results indicate that numerical multistep methods can provide an effective approach for population growth forecasting. The ABM4-based forecast provides a potential baseline for supporting government planning, including infrastructure development  and resource allocation.

## Tools
- Wolfram Mathematica

## Data Source
Population data for Penang, Malaysia, were obtained from the Department of Statistics Malaysia (DOSM).

## Project Files
- [Population_Growth_Forecasting.nb](Population_Growth_Forecasting.nb) - Mathematica notebook containing the computational analysis.
- [Population_Growth_Forecasting.pdf](Population_Growth_Forecasting.pdf) - Project presentation

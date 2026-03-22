# Busy or Not - Airport Security Screening

## Overview
Interactive dashboard that enables airport travelers to view predicted security throughput levels at desired and other nearby airports at every hour of the day.

## Problem
Airport travelers often face a lot of uncertainty with how long it will take to pass through security checkpoints and don't have the necessary data to easily compare how much time they may be able to save by choosing another departure time or even a completely different airport.

## Approach
Tested ARIMA, linear regression, random forest, XGBoost regression, and LSTM neural network models to evaluate performance. Determined that XGBoost regression was the best cost to performance balance so we created individual models for each airport in the United States. Airports were also grouped by size and location in order to better provide meaningful alternatives to users.

## Results
Interactive dashboard was created to allow for users to visualize security throughput at their chosen airport as well as nearby potential alternatives.

[View the project poster](ReportPoster.pdf)

## Notes
This project was completed as part of a graduate program in a team setting.  
Only the final report is shared here, and teammate names have been omitted for privacy.  

## My Contributions
- Participated in problem definition and planning methodology
- Created linear regression, XGBoost regression, and random forest models to compare for final model selection
- Automated XGBoost regression model training and test evaluation reporting for 455 individual airports
- Provided an API for the front end to predict security throughput at a given airport on a specified date/time while automatically determining alternative airports to predict and visualize as well
- Contributed to project poster development  

# E-scooter Usage and Safety in Stockholm

Analysis of ridership, fleet growth, and safety trends (2019–2023, Forecast to 2025)
“Over the years, we have steadily expanded our e-bike fleets... Stay tuned for what’s next!”
## Introduction

This analysis explores the growth, usage, and safety of e-scooters in Stockholm.
The purpose is to understand trends in ridership, fleet expansion, accident risk, and future outlook, to support decisions by city planners, operators, and policymakers.
## Data Source

All data comes from the Stockholm Miljöbarometern (Environmental Barometer) traffic statistics portal.
### Datasets used:

1. e_scooters_in_traffic – Number of e-scooters available in Stockholm.
2. e_scooter_daily_rides – Daily ridership counts (used to calculate annual rides).
3. e_scooter_accidents – Reported e-scooter accidents per year.
4. cykelpassager_citysnittet – Bicycle passages (city average), used for comparison.

## Workflow

## Python (Data Cleaning & Transformation)
Loaded raw CSVs from Miljöbarometern.
Cleaned missing values and standardized date formats.
Calculated annual rides from daily averages.


## Power BI (Visualization & Dashboard)

### Built interactive charts:
Fleet growth (2019–2023)
Rides and forecast (2020–2025)
Accident risk per ride (2021–2023)
Accident share vs. bicycles (2019–2023)
### Added KPIs and narrative context for storytelling.

### How to Read the Dashboard

#### Each chart answers a guiding question:
1. Fleet Growth → How many scooters are on the road?
2. Rides Forecast → How many rides are expected in the future?
3. Risk per Ride → How safe is it to ride?
4. Accident Share → Do scooters dominate accident statistics?

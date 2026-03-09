# Indian Railways Train Delay Analysis (Power BI)

PowerBI Dashboard on Indian Train Delay for the year 2025

## Overview

This project analyzes train delay patterns across Indian Railways using Power BI. The dashboard combines train delay data, station information, and calendar data to identify trends across divisions, stations, and time periods.

## Datasets Used

* **etrain_delays** – Contains train number, train name, station code, station name, and average delay in minutes.
* **Stations** – Includes station metadata such as division, state, category, and geographic coordinates.
* **Calendar** – Contains date, month, and day information for time-based analysis.

## Data Model

* `etrain_delays[STN_CODE]` → `Stations[STN_CODE]`
* Calendar table used for analyzing delays by day and month.

## Key Analysis

* Average delay by railway division
* Most delayed trains
* Delay trends by day of week and month
* Geographic visualization of delays across stations

## Tools

Power BI, DAX, Data Visualization

## Outcome

The dashboard provides insights into railway operational performance and highlights regions and trains with the highest delays.

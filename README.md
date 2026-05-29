# ENVS-193DS Homework 3

## General Information

This repository contains homework 3 for ENVS-193DS Spring 2026. 
The project analyzes personal bike commute data collected between 
home and UCSB to understand what factors influence travel duration. 
Data was collected by Michael Torbensen across two trials beginning 
April 14, 2026.

## Data and File Information

**Data file:** `personal_data.csv`

Variables included:
- `time_of_departure_hh_mm_24hr`: time of departure in 24hr format (continuous)
- `date_yyyy_mm_dd`: date of observation (continuous)
- `direction_of_trip`: direction of travel, either "home to UCSB" or "UCSB to home" (categorical)
- `trial_number`: trial number, either 1 or 2 (categorical)
- `distance_mi`: distance traveled in miles (continuous)
- `wind_speed_mph`: wind speed at time of departure in mph (continuous)
- `duration_mm_ss`: travel duration in mm:ss format (continuous)
- `stop_lights`: number of stoplights encountered (categorical)
- `type_of_transportation`: mode of transportation (categorical)

**Code file:** `code/Homework_quarto_doc.qmd` - Quarto document containing 
all analysis code and write-up.

## Rendered Output

The rendered document can be viewed at:
[Homework 3 Rendered Output](https://github.com/michaeltorbensen/ENVS-193DS_homework-03/blob/main/code/Homework_quarto_doc.pdf) 

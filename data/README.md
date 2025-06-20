# 📂 data/

This folder contains the raw dataset used in this project.

## Files

- **jakarta_traffic_data.csv**  
  The main dataset containing hourly traffic records in Jakarta.  
  It includes:
  - `Date` — Date of the traffic record
  - `Location` — Road segment/location in Jakarta
  - `Hour` — Time of day (0–23)
  - `Vehicle_Count` — Number of vehicles recorded
  - `Average_Speed_kmh` — Average vehicle speed (km/h)
  - `Weather_Condition` — Weather info (e.g. Sunny, Rainy)
  - `Is_Weekend` — Boolean indicating if the date is a weekend
  - `Road_Type` — Type of road (e.g. Main_Road, Highway)

> 📌 Note: Please ensure that this file is not modified directly. Use `src/preprocess.py` for any transformation.

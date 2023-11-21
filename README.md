# Final Project for I535
Please see the file details below:

### Ohio.png
This is the map visualization that is stored in the storage bucket

### Ohio_Dairy_2022.csv & Ohio_Dairy_2023.csv
These are the raw text files
Columns include:
- Program: Type of data collection, in this case the data it was via survey
- Year: Year
- Period: When the data was collected
- Week Ending: Null
- Geo Level: Geographical level of the data, in this case by county
- State: State
- State ANSI: State 2-digit ANSI code
- Ag District: Agricultural district
- Ag District Code: Code for the agricultural district
- County: County
- County ANSI: County ANSI code
- Zip Code: Zip code
- Region: Null
- watershed_code: Watershed district
- Watershed: Null, watershed district
- Commodity: Agricultural commodity
- Domain: Total
- Domain Category: N/A
- CATTLE, COWS, BEEF - INVENTORY  -  <b>VALUE</b>: Amount of beef cattle
- CATTLE, COWS, BEEF - INVENTORY  -  <b>CV (%)</b>:Amount of beef cattle %
- CATTLE, COWS, MILK - INVENTORY  -  <b>VALUE</b>: Amount of dairy cows
- CATTLE, COWS, MILK - INVENTORY  -  <b>CV (%)</b>: Amount of dairy cows %
- CATTLE, INCL CALVES - INVENTORY  -  <b>VALUE</b>: Amount of all cattle including calves
- CATTLE, INCL CALVES - INVENTORY  -  <b>CV (%)</b>: Amount of all cattle including calves %

### Query.xlsx
Results of running the query script

### cows_total.csv
Merged result of the Ohio_Dairy_YYYY files
- joined, but should have been unioned (merge vs concat)

### finalproj_packages.py
Python script for installing the packages necessary for running the lejohn_finalproj code

### lejohn_finalproj.py
Code for creating the Ohio map visualization

### query.py
Code for running the SQL script on the BigQuery table


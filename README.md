# singapore_unemployment_stats

A study in understanding unemployment stats in Singapore and analyzing if the following factors affect the trend:
- Gender discrimination and overall size of female workforce
- Productivity within an industry (value added)
- Resignation rates within industries
- Recruitment rates within industries
- Training and qualifications within the workforce
- Any other factors?

<b> Step 1: Data Extraction </b> <br>
Source: https://www.singstat.gov.sg/find-data/search-by-theme/economy/labour-employment-wages-and-productivity/latest-data

- Files were extracted in .xlsx format and studied using Google Sheets.
- From here I extracted the useful data, formatted it, removed null and empty values
- Downloaded all of that to csv files

<b> Step 2: Data Modelling </b>
- Wrote a python script to trawl through the data and reshape the tables so that they can be visualized better on Tableau.
- Need to run this through all the CSV files.

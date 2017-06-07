DATASET
Raw Incident Data, mostly oil spills, as gathered by NOAA's Office of Response and Restoration (OR&R).
Webpage: https://incidentnews.noaa.gov/ with some charts, a map and a report for each incident (e.g. https://incidentnews.noaa.gov/incident/7587)
We've downloaded the full dataset from https://incidentnews.noaa.gov/raw/index (May, 2017)

1. Exploration
- In OpenCalc, to see the data structure (a table) and its columns.
- Checking at webpage the variable and units used at each column.
- Transforming from gallons to litres (1 --> 3,78541) adding a new column
- Basic stats:
    * TOTAL: 3333 incidents
    * Maximum potential release (Total): 8834139922,5193 litres, although 1392 incidents lack of this data
    * Date range: from 1957-03 to 2017-05

- Created an exploratory map with Carto, showing every incident based on lat-lon data
[NOAA Incidents map](https://victorvelarde.carto.com/builder/db141284-98e5-4ec8-8994-5556b1064784/embed)

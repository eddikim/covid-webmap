# Web Mapping US COVID-19 Cases and Rates

<p> Using 2020 data on COVID-19 in the United States, two web map applications were designed to illustrate a thematic choropleth and proportional symbol map respectively. The choropleth map visualizes the number of cases per county with lighter colors indicating a lower count of COVID-19 cases and darker colors indicating a higher count of COVID-19 cases. As seen on this map, there are numerous counties with a high count of cases, especially concentrated around the state of California. The proportional symbol map illustrates the rate of COVID-19 per county with large pink buffers showcasing a higher rate, whereas smaller buffers show a smaller rate of COVID-19. While there are multitudes of smaller rates of COVID-19 all around the country, many of the counties with a higher rate of COVID-19 are seemingly concentrated across the middle region of the United States. The HTML code used to create these web map applications were founded on an existing web map application displaying earthquake magnitudes in Japan, with additional modifications made to work with the US COVID GeoJSON data files. </p>

# Screenshots of Maps

## [Choropleth Map (COVID-19 Cases)]

![map-1](/img/map1.jpg?raw=true)

## [Proportional Symbol Map (COVID-19 Rates)]

![map-2](/img/map2.jpg?raw=true)

# Data Sources
* [COVID-19 Case/Death Data][]
* [Population Data][]
* [U.S. County Shapefiles][]

# Credit

<p> Data was sourced from the New York Times, U.S. Census Bereau, and the American Community Survey (ACS) </p>

# Acknowledgement

<p> The lab was provided by Professor Zhao and Steven Bao. I appreciate both of them for helping to advance my learning in digital mapping. </p>

[COVID-19 Case/Death Data]: https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv
[Population Data]: https://data.census.gov/cedsci/table?g=0100000US.050000&d=ACS%205-Year%20Estimates%20Data%20Profiles&tid=ACSDP5Y2018.DP05&hidePreview=true
[U.S. County Shapefiles]: https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html
[Choropleth Map (COVID-19 Cases)]: http://127.0.0.1:5500/map1.html
[Proportional Symbol Map (COVID-19 Rates)]: http://127.0.0.1:5500/map2.html

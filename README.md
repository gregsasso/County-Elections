# County-Elections
This was the beginning of a project on using various machine learning models to try and predict election outcomes using demographic data. I'm not sure how much more I will be able to complete, but the code and data is here if it's useful for anyone. 

# Data Sources.
The data comes from various sources.
  - Unemployment data: Bureau of Labor Statistics, Local Area Unemployment Statistics: [Link](https://www.bls.gov/lau/tables.htm#cntyaa)
  - Demographic and Population data, US Census: [Link](https://www2.census.gov/programs-surveys/popest/datasets/). Datasets used are cc-est-2020-alldata6, cc-est-2022-alldata, co-est2020-aldata, co-est-2022-alldata
  - Election returns, 2016 - 2020, Replication Data for: Partisanship & Nationalization in American Elections: Evidence from Presidential, Senatorial, & Gubernatorial Elections in the U.S. Counties, 1872-2020: [Link](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DGUMFI)
  - Election returns, 2022, MIT Election Lab: [Link](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/YB60EJ)

# Data Description
The data in the main senate_county_wide.csv file is organized by county FIPS and election year. For example, if the FIPS is 1007, and the Year is 2016, then all data in that row corresponds with the 2016 election in county 1007. Columns with names ***_Year0 refer to data in the election year (ie, the unemployment rate in 2016). Columns with names ***_Year1 refer to data one year previous to the election (ie, the unemployment rate in 2015), and then similarly for ***_Year2. There are also columns denoting the percentage change between years. A column denoting CHANGE_YEAR_0, would be the percentage change in that variable from one year before the election (the relevant _YEAR1 value) to the year of the election (the relevant YEAR0 value). Similarly, CHANGE_YEAR_1 would be the change from 2 years before the election to 1 year before the election.

TK: More complete description of the variables.

# Project_One_Group_2

Project Description/Outline: We will investigate how the trends in the District of Columbia (DC) crime data may be affected by weather. We will use crime and weather data for the period February 2022 through February 2023. The study will include checking if there is a correlation between weather and crime rate. We want to know how the different weather conditions impact crime.
Create DC crime pandas dataframe.
  import the .csv data
  examine the data
  identify columns that we need
  filter based on above criteria

Create weather pandas dataframe.
  Gather weather data from Open Weather API regarding conditions over the last two years.
  Define what will be considered “good” versus “bad” weather conditions
  Compare conditions to the crime data and look for correlations

Cleaning data:

  Crime Data: 
One year’s worth of data was downloaded from crimecards.dc.gov which includes all crimes that were reported to the DC police department between February 1, 2022, and February 6, 2023.  That data was examined, and it was determined to create a new data frame consisting of columns that directly relate to the project’s goals.  All columns relating to the location of the reported offenses were determined to not add value to the project’s results.

The new data frame was then cleaned to have the reported “START_DATE” (the date the reported crime took place) into a separate column for both date and time.  Those were then converted to the corrected format to be consistent with the jointly collected weather data.  Incidents that had start dates prior to the reviewed period were also removed.  After the clean up there were 27,697 reported offenses included in the data frame

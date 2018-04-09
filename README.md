# Road Safety UK 2016

If you only want to know the results of this analysis, please view "Executive_Summary.pdf".

If you want to see my codes and how I did this analysis, please view "Master.Rmd".

You can find all the datasets, shapefiles and varible guide I was using under "data" folder.
The data I'm using here is [road safety data](https://data.gov.uk/dataset/road-accidents-safety-data) in UK 2016. There are 3 datasets: Accidents, Vehicle, Casualty. As it's easy to understand, an accident is mostly likely involve more than 1 vehicle, and it's likely to have multiple casualties from different vehicles. So Vehicle and Casualty are linked with Accidents by Accident_Index, Casualty and Vehicle are linked by Vehicle_Reference. You can find out how the varibles were coded in [Road Accident Safety Data Guide](https://github.com/daiyang94815/Road-Safety-UK-2016/blob/master/data/Road%20Accident%20Safety%20Data%20Guide.xls).

I also used [UK population data](https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/timeseries/gbpop/pop) in my analysis.

I got the UK shapefiles from [here](http://geoportal.statistics.gov.uk/datasets/local-authority-districts-december-2016-full-clipped-boundaries-in-great-britain).

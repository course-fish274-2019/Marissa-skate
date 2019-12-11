# Alaskan Trawl Data Analysis

The purpose is meant to answer the following questions: How do the distributions of known predator and prey compare? How do the distributions change with location, depth, and water temperature?

The original purpose was to gain familiarity with rmarkdown, creating slide presentations in r, and to gain mastery over ggplot and dplyr

Packages used: 

1. tidyverse, using ggplot2, tidyr, and dplyr to organize data

2. rnaturalearth, rnaturalearthdata for world map data

3. ggmap, maps and mapdata for map data as well

4. rgeos and sf for error-fixing/ map holes

Files in order of use:

1. scripts/TRAWL.Rmd - non-presentation rmarkdown file used to write code for presentation

2. data/ebs2017_2018 - data from three years of bottom trawls in the east Bering Sea. Original data at : https://www.fisheries.noaa.gov/resource/data/2017-2018-eastern-bering-sea-shelf-groundfish-bottom-trawl-survey-data)

3. data/ai2014_2018.csv - data from five years of bottom trawls in the Aleutian Islands. Original data at : https://www.fisheries.noaa.gov/resource/data/2014-2018-aleutian-islands-groundfish-bottom-trawl-survey-data)

4. data/bsslope2002_2016.csv - data from fifteen years of bottom trawls on the Bering Sea slope. Original data at : https://www.fisheries.noaa.gov/resource/data/2002-2016-bering-sea-upper-continental-slope-groundfish-bottom-trawl-survey-data)

5. data/goa2015_2017.csv - data from four years of bottom trawls in the Gulf of Alaska. Original data at : https://www.fisheries.noaa.gov/resource/data/2015-2017-gulf-alaska-groundfish-bottom-trawl-survey-data)

6. data/nbs1982_2018.csv - data from thirty-seven years of bottom trawls in the north Bering Sea. Original data at : https://www.fisheries.noaa.gov/resource/data/1982-2018-northern-bering-sea-shelf-groundfish-bottom-trawl-survey-data)

7. scripts/presentation.Rmd - presentation rmarkdown file used to write a slidy presentation for class

8. output/trawl.html - html export of knit rmarkdown file of TRAWL.Rmd

9. output/presentation.html - Slideshow made with slidy as export of RMarkdown file presentation.Rmd 

10. .gitignore -- github metadata

11. all files in .git folder, github metadata from comments and pushes

12. data_raw/ebs2017_2018 - data from three years of bottom trawls in the east Bering Sea. Original data at : https://www.fisheries.noaa.gov/resource/data/2017-2018-eastern-bering-sea-shelf-groundfish-bottom-trawl-survey-data) - not edited for use

13. data_raw/ai2014_2018.csv - data from five years of bottom trawls in the Aleutian Islands. Original data at : https://www.fisheries.noaa.gov/resource/data/2014-2018-aleutian-islands-groundfish-bottom-trawl-survey-data) - not edited for use

14. data_raw/bsslope2002_2016.csv - data from fifteen years of bottom trawls on the Bering Sea slope. Original data at : https://www.fisheries.noaa.gov/resource/data/2002-2016-bering-sea-upper-continental-slope-groundfish-bottom-trawl-survey-data) - not edited for use

15. data_raw/goa2015_2017.csv - data from four years of bottom trawls in the Gulf of Alaska. Original data at : https://www.fisheries.noaa.gov/resource/data/2015-2017-gulf-alaska-groundfish-bottom-trawl-survey-data) - not edited for use

16. data_raw/nbs1982_2018.csv - data from thirty-seven years of bottom trawls in the north Bering Sea. Original data at : https://www.fisheries.noaa.gov/resource/data/1982-2018-northern-bering-sea-shelf-groundfish-bottom-trawl-survey-data) - not edited for use

## Game Plan for the next two weeks (Written for week 11 quiz)

1. Add additional data from other arctic trawls and pelagic collections

2. Merge and organize new data and sort by +1000 Genus samples

3. Make at least one scatterplot and barplot to represent comparisons between two species

4. Figure out how to make code that saves as .rmd or presentation html

5. Figure out how to write script that runs other documents
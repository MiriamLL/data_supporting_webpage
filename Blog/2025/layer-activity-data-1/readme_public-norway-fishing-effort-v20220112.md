
## Norway VMS dataset
Downloaded date: Oct 25 2024 11:48 UTC
API Dataset versions: public-norway-fishing-effort:v20220112

### Description
Vessel monitoring system (VMS) data is provided by the The Norwegian Directorate of Fisheries. Data is collected using Norway’s vessel monitoring system via satellites and is published on a three-day delay containing information on vessels’ location, speed, course, and movement. Global Fishing Watch analyzes this data using the same algorithms developed for automatic identification system (AIS) to identify fishing activity and behaviors. The algorithm classifies each broadcast data point from vessels as either apparently fishing or not fishing and shows the former on the Global Fishing Watch’s fishing activity heat map. VMS broadcasts data differently from AIS and may give different measures of completeness, accuracy, and quality. Global Fishing Watch is continually improving its algorithms across all broadcast data formats to algorithmically identify “apparent fishing activity.” It is possible that some fishing activity is not identified or that the heat map may show apparent fishing activity when fishing is not actually taking place. For these reasons, Global Fishing Watch qualifies the terms “fishing activity,” “fishing” or “fishing effort,” as apparent rather than certain. Any and all Global Fishing Watch information about “apparent fishing activity” should be considered an estimate and must be relied upon solely at the user’s discretion. Global Fishing Watch’s fishing detection algorithms are developed and tested using actual fishing event data collected by observers and is combined with expert analysis of AIS vessel movement data, resulting in the manual classification of thousands of known fishing events. Global Fishing Watch also collaborates extensively with academic researchers through our research program to share fishing activity classification data and to improve automated classification techniques

Filters:  timestamp >= '2018-04-01T00:00:00.000Z' and timestamp <= '2018-05-31T00:00:00.000Z'
Group by: flagAndGearType
Temporal resolution: monthly (data is grouped by flagAndGearType and summarized by month)
Spatial aggregation: true


### Columns

* Time Range: The data format depends on the temporal resolution, for monthly (YYYY-MM), for daily (YYYY-MM-DD), for yearly (YYYY) and for entire the date-range query param value.
* flagAndGearType: flagAndGearType.
* Vessel IDs: Number of different vessel ids.

flagAndGearType.
* Apparent Fishing Hours: Hours that the vessel associated with this vessel_id was fishing in the grid cell over the selected time range


## License
Unless otherwise stated, Global Fishing Watch data is licensed under a Creative Commons Attribution-ShareAlike 4.0 International license and code under an Apache 2.0 license.

For additional information about:
these results, see the associated journal article: D.A. Kroodsma, J. Mayorga, T. Hochberg, N.A. Miller, K. Boerder, F. Ferretti, A. Wilson, B. Bergman, T.D. White, B.A. Block, P. Woods, B. Sullivan, C. Costello, and B. Worm. "Tracking the global footprint of fisheries." Science 361.6378 (2018). http://science.sciencemag.org/content/359/6378/904 
Data caveats and details: https://globalfishingwatch.org/dataset-and-code-fishing-effort/ 
	
## Suggested Citation

Global Fishing Watch. 2022, updated daily. Vessel apparent fishing effort v20220112, [Apr 01 2018 00:00 UTC May 31 2018 00:00 UTC]. Data set accessed 2024-10-25 at https://globalfishingwatch.org/map



## Chile VMS dataset
Downloaded date: Oct 25 2024 11:47 UTC
API Dataset versions: public-chile-fishing-effort:v20211126

### Description
Vessel monitoring system (VMS) data provided by the Chilean government’s fisheries and aquaculture regulator (SERNAPESCA). It is possible to filter Chile’s VMS data for small-scale fishing vessels (<18 meters) and industrial fishing vessels (>18 meters). Note that some vessels are <18 meters but are considered industrial because they were registered in the capture of industrial quotas. SERNAPESCA is also using our map to visualize and track vessel positions for their fleet, including vessels involved in aquaculture. Data is collected using Chile’s VMS via satellites and terrestrial receivers and contains vessel identities, gear type, location, speed, direction and more. Global Fishing Watch analyzes this data using the same algorithms we developed for automatic identification system (AIS) data to identify fishing activity and behaviors. The algorithm classifies each broadcast data point from vessels as either apparently fishing or not fishing and shows the former on the Global Fishing Watch map. VMS broadcasts data quite differently from AIS and may give different measures of completeness, accuracy and quality. Over time our algorithms will improve across all our broadcast data formats. Global Fishing Watch’s fishing presence algorithm for VMS, as for AIS, is a best effort to algorithmically identify “apparent fishing activity.” It is possible that some fishing activity is not identified, or that the heat map may show apparent fishing activity where fishing is not actually taking place. For these reasons, Global Fishing Watch qualifies the terms “fishing activity,” “fishing,” and “fishing effort,” as “apparent” rather than certain. Any/all Global Fishing Watch information about “apparent fishing activity” should be considered an estimate and must be relied upon solely at your own risk. Global Fishing Watch fishing presence algorithms are developed and tested using actual fishing event data collected by observers, combined with expert analysis of AIS vessel movement data resulting in the manual classification of thousands of known fishing events. Global Fishing Watch also collaborates extensively with academic researchers through our research program to share fishing activity classification data and automated classification.

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

Global Fishing Watch. 2022, updated daily. Vessel apparent fishing effort v20211126, [Apr 01 2018 00:00 UTC May 31 2018 00:00 UTC]. Data set accessed 2024-10-25 at https://globalfishingwatch.org/map


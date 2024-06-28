# hazard_data_release

This repository tracks the details and progress of the creation of hazard indices and metrics from Australian Climate Service (ACS) CORDEX-CMIP6 data and other data for use in the National Climate Risk Assessment.

Dataset specifications

Data availability

The table below provides a summary of what data has been processed.

The three dots (in order from first/top/left to last/bottom/right) represent:

In terms of the colors:
- :green_circle: The data is available in its final official form 
- :yellow_circle: The indice data exists for beta users to try
- :white_circle: Not yet processed but we don't anticipate any problems/delays
- :red_circle:  

Last update: Mon 3 June 6:30am: 



| Hazard | PI  | GWL1.2 | GWL1.5  | GWL2.0 | GWL3.0 | GWL4.0| (Notes) |
| ---    | --- | ---    |  :-:    | :-:    | :-:    | :-:   | :-:     |
| **Ocean (OFAM)**|     |        |         |        |        |       |         |
| SST monthly climatology     |:white_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | data stored on /g/data/ia39/ncra/ocean |
| MWH duration |:white_circle: | :yellow_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | /g/data/ia39/ncra/ocean  |
| MHW intensity|:white_circle: | :yellow_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | /g/data/ia39/ncra/ocean  |
| surface pH monthly climatology   |:green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | /g/data/ia39/ncra/ocean  |
| surface aragonite saturation state monthly climatology |:green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: |/g/data/ia39/ncra/ocean |
| **Heat**|     |        |         |        |        |       |         |
| Daily maximum surface air temperature (tasmax)   |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| TXx (hottest day   |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| TX90p    |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| EHF number    |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| EHF duration  |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| **Fire**|     |        |         |        |        |       |         | 
| FFDI     |:white_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :white_circle: | /g/data/ia39/ncra/fire |
| Fire climate classes     |:white_circle: | :yellow_circle: | :yellow_circle: | :yellow_circle: | :yellow_circle: | :white_circle: | data stored on /g/data/ia39/ncra/bushfire |
| Fire climate classes shifts     |:white_circle: | :yellow_circle: | :yellow_circle: | :yellow_circle: | :yellow_circle: | :white_circle: | data stored on /g/data/ia39/ncra/bushfire |
| **Extreme Prec.**|     |        |         |        |        |       |         |
|Average Daily Rainfall    |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
|RX1h (heaviest hourly total per year)     | | :yellow_circle: | :yellow_circle: | :yellow_circle: | :yellow_circle: | | data stored on /g/data/ia39/ncra/extratropical_storms/ |
|RX1D (heaviest daily total per year)  || :yellow_circle: | :yellow_circle: | :yellow_circle: | :yellow_circle: |  |  data stored on /g/data/ia39/ncra/extratropical_storms/ |
|RX5D (heaviest 5 day total per year)  | | :yellow_circle: | :yellow_circle: | :yellow_circle: | :yellow_circle: | |  data stored on /g/data/ia39/ncra/extratropical_storms/ |
| **Tropical Cyclones**|     |        |         |        |        |       |         |
| Cyclone frequency |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| Cyclone Intensity |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| **Extratropical Storms (NESP portal)**|     |        |         |        |        |       |         |
| Number of tracked surface low-pressure systems   | | :green_circle: | :green_circle: | :green_circle: | :green_circle: |  | data stored on /g/data/ia39/ncra/extratropical_storms/ |
| **Riverine and Flash Flooding (NHP)**|     |        |         |        |        |       |         |
|Runoff (RX1 - median annual max 1-day runoff)  |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| **Drought**|     |        |         |        |        |       |         |
| SPI    |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| Drought duration    |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| **Coastal Inundation**|     |        |         |        |        |       |         |
| extreme water level(canute2)     |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| Regional Sea Level Rise (CMIP6 projection)     |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| Aggregation of flood days |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| 1 in 100 AEP inundation |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| **Coastal Erosion**|     |        |         |        |        |       |         |
|     |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| **Convective Storms**|     |        |         |        |        |       |         |
|         |:white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: | :white_circle: |  |
| ---    | --- | ---    |  :-:    | :-:    | :-:    | :-:   | :-:     |

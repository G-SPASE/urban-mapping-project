# urban-mapping-project
Urban Mapping Project wiki

# GitHub repositories
- Project overview (here): https://github.com/G-SPASE/urban-mapping-project
- POI filter tool (private): https://github.com/G-SPASE/osmdata
- Bing image downloading tool (private): https://github.com/G-SPASE/bingaerial-downloader
- OSM transportation network data quality assessment tool (private): https://github.com/G-SPASE/road_evaluation

# Project overview
## Data collection in Yangon
- [x] Road Network and building boundary data collection (existing)
- [x] Road network, building boundary, POI collection from OSM
- [x] SNS data and Geo-tagged photo collection
- [x] Satellite imagery collection and processing (Yamamoto with the shared tool)

## Data validation
- [x] Transportation network data assessment tool for connectivity and error estimation

## Modules / tools
- [x] Road network creation from OSM
	  - Upload to GitHub
- [x] Download imagery
	  - Shell script (args: two xy coordinates)
	  - [x] Documentation
	  - [x] Share tool
- [x] Detect vehicles
	  	- Input: tiff
	  	- Output: Image, vehicle positions, georeferenced point
		- [x] Documentation and sample input and output
		- [x] Geo-referenced result
- [x] Detect clusters of vehicle and transportation network
	  - Road network (OSM)
      - Unit density (km/km^2) = Line length / spatial unit
      - (Accessibility (km/km^2) = Total distance accessible in one hour)
    - Vehicle detection
      - Number of vehicle (N/km^2)
    - Building detection
    - Area of Buildings
- [x] Route API between POIs
	  - Documentation
	  - (Product)
- [x] Web client application

## Applications for urban problems
- [x] OSM transportation network data quality assessment tool

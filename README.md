# urban-mapping
Urban Mapping Project wiki

## Data collection in Yangon
- [x] Road Network and building boundary data collection (existing)
- [x] Road network, building boundary, POI collection from OSM
  - [x] SNS data and Geo-tagged photo collection
  - [ ] Satellite imagery collection and processing (Yamamoto with the shared tool) 
	  - [ ] Store in S3

## Data validation
  - [ ] Transportation network data assessment tool for connectivity and error estimation (Tandang)
  - [ ] Building boundary (OSM and existing data) (Miyazawa)
	- ArcGIS
		- OSM building + Detected building images
		- Calculate area / building boundaries -> accuracy

## Modules / tools
- [ ] Road network creation from OSM (Xia)
	  - Upload to GitHub
- [x] Download imagery (Koga)
	  - Shell script (args: two xy coordinates)
	  - [ ] Documentation
	  - [ ] Share tool (1. Upload to GitHub, 2. Send to Xia-san or Miyazawa)  
- [ ] Detect vehicles (Koga)
	  	- Input: tiff
	  	- Output: Image, vehicle positions, georeferenced point
		- [ ] Documentation and sample input and output
		- [ ] Geo-referenced result
			- [ ] Geo-referenced image + result
			- [ ] Georeference vehicle objects
- [ ] Detect clusters of vehicle and transportation network (Miyazawa)
	  - Road network (OSM)
      - Unit density (km/km^2) = Line length / spatial unit
      - Accessibility (km/km^2) = Total distance accessible in one hour
    - Vehicle detection
      - Number of vehicle (N/km^2)
    - Building detection
    - Area of Buildings
- [ ] Detect Buildings (Koga)
  		- Input: tiff
  		- Output: Image, result image
  		- [ ] Documentation and sample input and output
	  	- [ ] Georeference result image
- [ ] Route API between POIs (Xia)
	  - Documentation
	  - Product
- [ ] Web client application (Xia)

## Applications for urban problems
- [ ] Transportation cluster detection with road network from OSM and vehicle detection from aerial imagery (Miyazawa)
- [ ] Web-based routing application between POIs for tourists (Xia)

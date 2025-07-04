# NYC Crosswalk Detection with Machine Learning
Detects crosswalks in NYC using Google Earth Engine and machine learning, exports their coordinates, and visualizes them on an Esri map.

**Tech Stack**
- Google Earth Engine 
- Python
- JavaScript
- Esri API
- HTML
- CSS

**Key Features**
- Uses ML in Google Earth Engine to detect crosswalks from satellite imagery
- Retrieves longitude and latitude of detected crosswalks
- Exports data to CSV for local processing
- Converts CSV data to JavaScript for Esri map integration
- Visualizes detected crosswalk locations on an interactive map

**Lessons Learned**
- Using GEE for machine learning classification on satellite imagery
- Introduction to machine learning in an untraditional manner
- Efficiently handling coordinate data
- Integrating custom data layers into Esri maps

**Areas for Improvement**
- Automate CSV to JS conversion pipeline
- More accurate results
- Add filtering by borough or confidence threshold
- Improve visualization with clustering for dense areas

**Setup Instructions**

*Run Detection on GEE:*
- Use the provided GEE script to detect crosswalks.
- Export CSV of detected coordinates.

*Convert CSV:*
- Use the provided Python script or manual method to convert CSV data to a .js file

*View on Esri Map:*
- Open the Esri map project and ensure your .js data file is correctly referenced
- View detected crosswalks on the map

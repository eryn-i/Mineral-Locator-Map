## The Mineral Locator Map sponsored by The Daily Beast

This map was developed for The Daily Beast news platform as a tool for their clients to expand their knowledge of rockhounding. The Mineral Locator Map details the locations of precious and semi-precious stones across the North, Central, and South American continents. If the clients find the BaseMap unsatisfactory, a map control function was included to easily switch between the BaseMap, Stamen Map, Esri World Street Map, and the Esri World Imagery map. Assets include valuable minerals such as Diamond, Emerald, and Garnet. The map utilizes choropleth symbolization and the chroma.js library to display the number of mineral locations known per Country or US State as an interactive world map. The symbolization is defined as Locations per Country, where each of the 5 colors is delegated according to 0 minerals up to 50+ minerals. Clicking on a mineral-populated Country or US State will automatically zoom the client to that area and display new popups. These popups contain information relevant to the minerals and the Country of focus, the top minerals of that country, and a link to the Wikipedia page for that mineral. Hovering over a gemstone icon will display the mineral's name, location from the USGS Mineral Resources Data System, and associated Country or US State. 

[Referenced Article](https://www.thedailybeast.com/rockhoundingthe-socially-distant-hobby-that-might-make-you-rich/)

## Packages, Stylesheets and Data 
- **Leaflet.js** (for map creation and customization)
- **GeoJSONson.io** (for formatting and converting GeoJSONson files)
- **jQuery** (for handling DOM manipulation and event handling)
- **Leaflet.css, and Google Fonts** (stylesheets for the design of the user interface)
- **FontAwesome** (for custom icons)
- **Chroma.js** (for color conversions and color scales)
- **Wikipedia, the free encyclopedia** (for additional mineral information)

**Data Provided by:**
- USGS Mineral Resources Data System (stones.geojson)
The [Esri ArcGIS Data and Maps: US State Boundaries GeoJSON](https://hub.arcgis.com/datasets/TrainingServices::us-state-boundaries/about) file was aquired after some completion of the map and reformatted to combine it with the [ESRI ArcGIS Hub Training Services: World Countries Generalized Geographic Boundaries](https://hub.arcgis.com/datasets/esri::world-countries-generalized/about) file as one GeoJSON polygon file (maps.geojson). 

Map authored by Eryn Stowe

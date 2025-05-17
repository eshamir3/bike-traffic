# Bikewatching

An interactive visualization of bike traffic patterns in the Boston area using Mapbox and D3.js.

## Features

- Interactive map showing bike lanes in Boston and Cambridge
- Real-time visualization of bike station traffic
- Time-based filtering to see traffic patterns throughout the day
- Color-coded stations based on traffic flow (arrivals vs departures)
- Responsive design with tooltips showing detailed station information

## Setup

1. Clone this repository
2. Get a Mapbox access token from [Mapbox](https://www.mapbox.com/)
3. Replace `YOUR_ACCESS_TOKEN_HERE` in `map.js` with your Mapbox access token
4. Open `index.html` in a web browser

## Data Sources

- Boston bike lanes: [Boston Open Data](https://bostonopendata-boston.opendata.arcgis.com/datasets/boston::existing-bike-network-2022.geojson)
- Cambridge bike lanes: [Cambridge Open Data](https://opendata.arcgis.com/datasets/2d1a3a2a0c4e4c4e9e9e9e9e9e9e9e9e_0.geojson)
- Bluebikes station data: [Bluebikes System Data](https://dsc106.com/labs/lab07/data/bluebikes-stations.json)
- Bluebikes trip data: [Bluebikes Trip Data](https://dsc106.com/labs/lab07/data/bluebikes-traffic-2024-03.csv)

## Technologies Used

- Mapbox GL JS for map visualization
- D3.js for data visualization and manipulation
- HTML5, CSS3, and JavaScript (ES6+)

## License

MIT License 
# Carolina Election Desk

A responsive, county-level North Carolina election-results dashboard.

## Run locally

Serve this directory over HTTP (the map loads its local GeoJSON file):

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Data notes

All vote shares and vote counts in the interactive preview are generated sample data. They are not official 2026 election returns, projections, or voter data. County outlines are based on the Plotly `geojson-counties-fips` dataset, which contains U.S. Census county geography; this site filters it to North Carolina and rounds boundary coordinates for display.
# U.S. Domestic Airport Network Analysis (2025)


Network analysis of U.S. domestic air traffic using BTS T-100 segment data. 
Includes Louvain community detection, hub dependency analysis, and betweenness 
centrality visualization.

## Files
- `analysis.ipynb` — full analysis notebook
- `index.html` — interactive Folium network map
- `requirements.txt` — Python dependencies



## Data Sources
Historical data from Bureau of Transportation Statistics: https://www.bts.gov/browse-statistical-products-and-data/bts-publications/data-bank-28ds-t-100-domestic-segment-data
The December 2025 file was used; this included Jan - Dec of 2025

Airport location data from OpenFlights.org: https://openflights.org/data
https://raw.githubusercontent.com/jpatokal/openflights/master/data/airports.dat

Note: 
Passenger counts reflect enplaned segment passengers as reported in BTS Form T-100 
(DB28), not true origin-to-destination volumes. A connecting passenger traveling 
through an intermediate hub is counted once per segment, causing hub airports to appear 
inflated relative to their true origin-to-destination traffic. Analyses of relative hub importance and network 
structure remain valid, but absolute passenger figures should be interpreted as segment-level 
activity rather than end-to-end travel demand.

Folium Map:
<a href="https://danny-m-22.github.io/Airport-Network-Analysis/">
  <img width="1363" height="786" alt="image" src="https://github.com/user-attachments/assets/23b0247f-c3bc-4ae6-a5ea-ad830037fd07" />
</a>
<p><em>Click the image above to view the interactive airport network map.</em></p>

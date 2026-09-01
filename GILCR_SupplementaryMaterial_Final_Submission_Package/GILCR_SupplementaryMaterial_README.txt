SUPPLEMENTARY COMPUTATIONAL MATERIAL

Manuscript:
Quantifying cooling-related health benefits from urban green infrastructure in life cycle impact assessment

Journal:
Sustainable Production and Consumption

MAIN NOTEBOOK
- GILCR_SupplementaryMaterial_Final_Submission.ipynb

REQUIRED LOCAL INPUT FILES
Place these files in the same directory as the notebook:
- centralpark_USW00094728_tmax_20220601_20220831_daily.csv
- laguardia_USW00014732_tmax_20220601_20220831_daily.csv
- webplotdigitizerRR_T.csv

SPATIAL DATA
The notebook can download the official public spatial datasets on first execution.
The U.S. Census population API requires a Census API key unless a cached/local
population file is supplied.

For a fully self-contained/offline archive, also include the lcr_spatial_cache/
directory from a successful local run, especially:
- central_park_parks_properties.geojson
- manhattan_2020_census_blocks.geojson
- manhattan_2020_block_population.csv
- nyc_borough_boundaries.geojson

Aerial imagery is visualization-only and does not affect analytical LCIA results.

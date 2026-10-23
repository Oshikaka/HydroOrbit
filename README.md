# HydroORBIT data audit

Interactive dashboard: **https://oshikaka.github.io/HydroOrbit/**

Consistency audit of the CAMELSH hourly point cloud (9,008 US basins) against ERA5-DAYMET (daily, 10′ grid), 1980–2021: leap-year alignment, Daymet day boundaries, variable agreement, correlations and rain-to-flow lags. The **ERA5 0.25° US** tab shows the hourly ERA5 0.25° archive cropped to the ERA5-DAYMET window (120 × 240 native cells, 1979–2020): hourly fields for three weather events, hourly city series, 1980–2020 agreement with ERA5-DAYMET, a 24-hour window scan, and a provenance check of the fields ERA5-DAYMET labels as Daymet. The **Datasets** tab lists every variable, unit and summary statistic for ERA5 0.25° (hourly), ERA5-DAYMET 10′ (daily) and CAMELSH (hourly).

The page is static: `index.html` loads `data/meta.json` and the base64 array files in `data/`. To view locally, serve the folder (`python -m http.server`) rather than opening the file directly.

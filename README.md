# HydroORBIT data audit

Interactive dashboard: **https://oshikaka.github.io/HydroOrbit/**

Consistency audit of the CAMELSH hourly point cloud (9,008 US basins) against ERA5-DAYMET (daily, 10′ grid), 1980–2021: leap-year alignment, Daymet day boundaries, variable agreement, correlations and rain-to-flow lags. The **Datasets** tab lists every variable, unit and summary statistic for ERA5 0.25° (hourly), ERA5-DAYMET 10′ (daily) and CAMELSH (hourly).

The page is static: `index.html` loads `data/meta.json` and the base64 array files in `data/`. To view locally, serve the folder (`python -m http.server`) rather than opening the file directly.

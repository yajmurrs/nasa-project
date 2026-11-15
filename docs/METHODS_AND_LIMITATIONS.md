# Model and interpretation

Three lunar south-pole sample points: MM-01 (-85.4, 31.7 E), MMP-02 (-84.3, 30.6 E), NR-03 (-85.4, 37.3 E). 721 hourly UTC samples, 2026-11-14 through 2026-12-14.

NASA LOLA-derived 20 m and 80 m terrain DEMs support an experimental local-horizon model, with the distant scan to approximately 80 km. JPL Horizons provides the Sun and Earth azimuth and elevation. A sampled center is unobstructed if its elevation exceeds the modeled terrain horizon in its azimuth direction.

**Limitations:** This is not full-disk illumination, a radio link budget, an operational hazard model, or a certified landing-site comparison. Results depend on near-field exclusion distance, interpolation, observer displacement and vertical reference assumptions. 20 m pixels do not resolve small rocks or meter-scale hazards. USGS navigational-grid coverage is not the same as formal landing-region boundaries. Nearby reference estimates are not separately computed visibility forecasts. The current static HTML uses embedded precomputed values, not live Horizons/DEM calculations.

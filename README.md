# SHE’AR FORCE — Lunar Landing Site Navigator

**NASA Space Apps Challenge 2026 · Research prototype**

A cinematic lunar south-pole explorer with three modeled locations, Sun/Earth center-line visibility summaries, and coordinate data-availability warnings.

## Launch
Open `index.html` in a browser. No build step is necessary. To publish, enable **Settings → Pages → Deploy from branch → main → / (root)** after uploading the website HTML.

## Sample locations

| Site | Latitude | East longitude | Sun clear / 721 | Earth clear / 721 | Both clear / 721 |
|---|---:|---:|---:|---:|---:|
| MM-01 | -85.4 | 31.7 | 388 | 690 | 388 |
| MMP-02 | -84.3 | 30.6 | 193 | 436 | 193 |
| NR-03 | -85.4 | 37.3 | 216 | 0 | 0 |

Figures are **experimental counts of unobstructed modeled Sun/Earth centers at hourly sampling instants**, not certified continuous durations, communications links, or landing-site safety assessments.

## Scientific background

The model uses NASA LOLA topography (20 m near-field and 80 m distant terrain) with NASA JPL Horizons ephemerides, and considers nearest/bilinear raster sampling. Coordinate-grid coverage does not establish a NASA-approved landing site. Nearby-coordinate outputs must not be interpreted as newly computed results.

See [sources](docs/SOURCES.md) and [limitations](docs/METHODS_AND_LIMITATIONS.md).

## Attribution and open source

MIT licensing applies only to original project software to which contributors hold rights. NASA/JPL/USGS material and third-party components retain their respective terms. No NASA endorsement is implied.

**Deployment note:** The website source `index.html` needs to be uploaded from the original cinematic HTML file before GitHub Pages can show the site.

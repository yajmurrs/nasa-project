# SHE’AR FORCE — Lunar Landing Site Navigator

An open-source cinematic lunar south-pole exploration prototype created for NASA Space Apps 2026.

## View and run the website

- **Live site (after initial Pages setup):** https://yajmurrs.github.io/nasa-project/
- **Run locally:** Click **Code → Download ZIP**, extract the archive, then double-click **`index.html`** in Chrome, Edge or Firefox. **No Node.js, Python, npm, environment variables or server are required.**
- **For developers:** `git clone https://github.com/yajmurrs/nasa-project.git`, then open `index.html`.

## One-time GitHub Pages setup

The repository includes `.github/workflows/deploy.yml`, which deploys `index.html` on every commit to `main`.

1. Upload the complete final cinematic website as **`index.html`** in the repository root. Without it the deploy cannot succeed.
2. On GitHub, go to **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. Open **Actions** to confirm the workflow succeeded.

The visual design is preserved in the single HTML file. It embeds CSS and JavaScript; Google Fonts are optional external web resources.

## Model overview

The research prototype compares three lunar south-pole sample locations using NASA LOLA-derived terrain and JPL Horizons Sun/Earth angles.

| Site | Latitude | East longitude | Sun clear | Earth clear | Both clear |
|---|---:|---:|---:|---:|---:|
| MM-01 | -85.4 | 31.7 | 388/721 | 690/721 | 388/721 |
| MMP-02 | -84.3 | 30.6 | 193/721 | 436/721 | 193/721 |
| NR-03 | -85.4 | 37.3 | 216/721 | 0/721 | 0/721 |

Values are **experimental** hourly sampled center-sightline classifications, not certified illumination durations, communication links or landing safety assessments. Nearby-coordinate reference outputs are not independent point-specific simulations.

See [data sources](docs/SOURCES.md) and [methods and limitations](docs/METHODS_AND_LIMITATIONS.md).

## Licensing

The MIT license applies to original team-authored code; third-party imagery, data and libraries retain their terms. No NASA endorsement is implied.

# ChaosLens
A browser-local time-series detective by Jeffery Rao.

Open `dist/index.html` or serve `dist` with any static server. No build or dependencies.

## Features
- CSV upload (quoted fields supported), numeric signal and timestamp selection
- Missing values, sampling integrity, robust unusual-point checks, chronological mean shift
- Time-series chart, 2D delay embedding, autocorrelation
- Three reproducible demos and downloadable JSON findings / source CSV

All CSV processing happens in the browser. No analytics or remote dependencies.

## Scientific limits
These are exploratory heuristics. An embedding does not establish chaos. Mean-shift scores are not significance tests. CSV inspection cannot establish absence of ML leakage. Outliers are not automatically errors. Row-based autocorrelation needs careful interpretation for irregular data.

## Next
Reproducible Python export, statistical validation, baseline forecasting, and accessible SVG figure export.

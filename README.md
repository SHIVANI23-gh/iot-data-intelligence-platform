# IoT Data Intelligence Platform

A browser-based sensor analytics workspace for exploring IoT-style CSV datasets.

## Features
- Upload and inspect CSV sensor datasets in the browser
- View missing values, duplicate rows, numeric summaries, and outlier candidates
- Explore correlations and visualize sensor readings
- Detect unusual readings and test a simple forecast
- Try built-in sample datasets and a clearly labelled virtual IoT simulator
- Keep uploaded dataset processing in the browser; the page does not upload your CSV to a server

## Run locally
Open `index.html` in a modern web browser. No build step or server is required for this static prototype.

## Publish with GitHub Pages
1. Create a GitHub repository (for example, `iot-data-intelligence-platform`).
2. Upload `index.html` and `README.md` to the repository root and commit the changes.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for the deployment to finish. The site URL will be shown on the Pages settings screen and will usually look like `https://YOUR-USERNAME.github.io/iot-data-intelligence-platform/`.

## Prototype limitations
This is a static, browser-only prototype. Forecasting and anomaly detection are simple built-in methods; the simulator uses generated readings, not physical device data. A backend, database, Excel `.xlsx` upload, and live LLM/API-powered explanations are not included in this version.

# Human Design Chart Calculator

A simple web frontend for the [hd-chart-api](https://github.com/jarlehildrum/hd-chart-api).

Enter your birth date, time, and place to calculate your Human Design chart.

## Live Demo

👉 https://jarlehildrum.github.io/hd-chart-web/

## Setup

This is a static single-page app — no build step needed.

### Local development

```bash
# Start the API
cd ~/projects/hd-chart-api/HdChartApi
dotnet run

# Serve the frontend (any static server works)
cd ~/projects/hd-chart-web
python3 -m http.server 8080
```

Open http://localhost:8080 and set the API URL to `http://127.0.0.1:5100`.

### GitHub Pages

The site is deployed automatically from the `main` branch via GitHub Pages.

For the demo to work publicly, the API must be accessible from the internet
(e.g. via Cloudflare Tunnel).

## Features

- Birth date, time, and place input
- Type, profile, strategy, authority, definition
- Incarnation cross
- All 9 centers (defined/undefined)
- Active channels
- Full personality and design activations with planet symbols
- Dark theme, mobile responsive
- Configurable API URL (saved in localStorage)

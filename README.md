# GPX Collection Viewer

A Python tool that generates beautiful static HTML pages with interactive
Leaflet maps to visualize collections of GPX files. Perfect for organizing and
sharing GPS tracks from hiking, cycling, running, or any GPS-recorded
activities.

## Features

- **Interactive Maps**: View GPX tracks and waypoints on beautiful interactive maps powered by Leaflet
- **Collection Organization**: Organize GPX files into collections using folder structure
- **Multiple Map Layers**: Support for Mapbox outdoor and satellite map layers (optional)
- **Responsive Design**: Mobile-friendly interface with collapsible sidebars
- **Markdown Content**: Add descriptions and content to collections using markdown files
- **File Downloads**: Direct download links for original GPX files
- **Track Highlighting**: Click on filenames to zoom and highlight specific tracks
- **Overview Map**: Master overview page showing all collection locations

## Quick Start

1. **Install**:
   ```bash
   pip install gpxcollection
   ```

2. **Organize your GPX files**:
   ```
   input/
      hiking-trails/
         trail1.gpx
         trail2.gpx
         index.md (optional description)
      cycling-routes/
         route1.gpx
         route2.gpx
      running-tracks/
         morning-run.gpx
   ```

## Usage

### Basic Usage

```bash
gpxcollection INPUT_DIR OUTPUT_DIR
```

### With Mapbox Tokens (Recommended)

For enhanced map layers, obtain Mapbox access tokens and use:

```bash
gpxcollection input/ output/ --mapbox_outdoor_token YOUR_TOKEN --mapbox_satellite_token YOUR_TOKEN
```

# Geospatial Analysis with DuckDB and Mapbox

A Jupyter notebook walkthrough of geospatial analysis using DC public schools and address data.

## Prerequisites

- [uv](https://docs.astral.sh/uv/getting-started/installation/) — Python package manager
- [QGIS](https://qgis.org/download/) — for visualizing spatial data (optional but recommended). Install the QuickMapServices plugin for basemap functionality.
- A [Mapbox account](https://account.mapbox.com/auth/signup/) with a free access token

## Setup

**1. Install uv**

On macOS/Linux:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

On Windows:
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

**2. Clone this repo and install dependencies**

```bash
git clone https://github.com/sbma44/georgetown-lecture-20260408-GBUS4401.git
cd georgetown-lecture-20260408-GBUS4401
uv sync
```

**3. Launch the notebook**

```bash
uv run jupyter notebook
```

Then open `geospatial_analysis.ipynb`. The notebook will walk you through the rest.

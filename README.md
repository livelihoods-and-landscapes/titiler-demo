# Demo Titiler - dynamic web map tile generator


### 1. Install packages

```
pip install titiler folium requests

```

### 2. Setup TiTiler 

Titiler is a dynamic tiler server that can read data from a COG file and generate web map tiles.

`cd` into app directory. Launch TiTiler application:

```
uvicorn main:app --reload
```

### 3. Visualise web map tiles

`cd` to main directory. Launch *cog-demo.ipynb*
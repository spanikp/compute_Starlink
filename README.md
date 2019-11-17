# Compute Starlink satellite position
Starlink is planned constellation build by SpaceX which should provide high bandwidth and fast connection to the internet worldwide. So far (state of November, 2019) there were two launches which carries 60 Starlink satellites each, so there are 120 satellites currently orbiting the Earth.

Jupyter notebook `SpaceX_Starlink_satpos.ipynb` shows how we can easily compute Starlink satellite positions from publicly available data.

## Requirements

Create a new virtual environment `compute_Starlink` using conda with following packages and activate this environment:

```
conda create -n compute_Starlink python=3.7 pandas beautifulsoup4 requests astropy jupyter
conda activate compute_Starlink
```

Some packages needs to be installed via pip:

```
python -m pip install pycraft sgp4
```

 
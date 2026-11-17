# Power Outage in Texas from Extreme Weather in 2021

<p align="center">
  <img src="image/texas.jpeg" alt="texas" width="600">
</p>

## Purpose of repository


This repository contains the materials for the [fourth homework assignment](https://eds-223-geospatial.github.io/assignments/HW4.html) for EDS 223: Geospatial Analysis and Remote Sensing, a course that is part of the [Master of Environmental Data Science program](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) completed at the Bren School of Environmental Science and Management.

## Background




## Data information and organization

For this assignment, we will use NASA's Worldview to explore the data surrounding the event date for the storm in Houston. The two dates that were chosen were Febraury 7 and February 16, 2021 due to clearer images to help visualize the extent of the power outage.

Also, utilizing road data will help minimize any false imagery that may be incorporated as nights with less traffic since roads give off a fair amount of light on its own.
```
extreme_weather_impact
.
├── data
│   ├── gis_osm_buildings_a_free_1.gpkg
│   ├── gis_osm_roads_free_1.gpkg
│   └── VNP46A1
│       ├── VNP46A1.A2021038.h08v05.001.2021039064328.tif
│       ├── VNP46A1.A2021038.h08v06.001.2021039064329.tif
│       ├── VNP46A1.A2021047.h08v05.001.2021048091106.tif
│       └── VNP46A1.A2021047.h08v06.001.2021048091105.tif
├── extreme_weather_impact.qmd
├── image
│   └── texas.jpeg
└── README.md
```

The `data` folder houses all the main data to reproduce this analysis. The data for the Visible Infrared Imaging Radiometer Suite (VIIRS) was prepped and given by the instructed in a file called `VNP46A1`. This file houses all four of the necessary files, which correspond to two dates (before and after the storm) and the two borders of tiles, h08v05 and h08v06, for Houston. The VIIRS data is distributed through NASA's [Level-1 and Atmospheric Archive & Distribution System](https://ladsweb.modaps.eosdis.nasa.gov/).

The remaining two datasets are for the roads `is_osm_roads_free_1.gpkg` and buidlings `gis_osm_buildings_a_free_1.gpkg` in Houston. Both of these come from [Geofabrik's downloades sites](https://download.geofabrik.de/), which was redistributed from [OpenStreetMap (OSM)](https://planet.openstreetmap.org/).


## References

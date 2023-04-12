# GeoPandas Basics

You can read the instructions about this workflow on [Linkedin](https://www.linkedin.com/posts/istanbul-data-science-academy_istdsa-b%C3%BClten-13-geopandas-activity-7051846117117857792-CLwk?utm_source=share&utm_medium=member_desktop).

![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)

## What is GeoPandas and when to use?

![GeoPandas](https://geopandas.org/en/stable/_images/geopandas_logo.png)

- GeoPandas is an open source project to add support for geographic data to pandas objects. 
- The core data structure in GeoPandas is the `geopandas.GeoDataFrame`, a subclass of `pandas.DataFrame`, that can store geometry columns and perform spatial operations.

<p align="center">
  <img src="https://autogis-site.readthedocs.io/en/2019/_images/geodataframe.png" />
</p>

- The `geopandas.GeoSeries`, a subclass of `pandas.Series`, handles the geometries. 
- Therefore, your GeoDataFrame is a combination of `pandas.Series`, with traditional data (numerical, boolean, text etc.), and `geopandas.GeoSeries`, with geometries (points, polygons etc.).

## Datasets

- [NYC Borough Boundaries](https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm)

![NYC Borough Boundaries](https://secretnyc.co/wp-content/uploads/2021/02/NYC-neighborhood-borders.png)

- [NYC Subway Stations](https://data.cityofnewyork.us/Transportation/Subway-Stations/arq3-7z49)

![NYC Subway Stations](https://new.mta.info/sites/default/files/2021-10/Screen%20Shot%202021-10-19%20at%202.14.23%20PM.png)

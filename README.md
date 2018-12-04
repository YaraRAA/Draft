# Draft

This R code is based on the original python code created by Giovanni Zambotti and can be found here:
https://github.com/gzambotti/pm/tree/master/newengland

The code:
- Imports into R a .csv file with longitude, latitude and Unique ID for each point
- Projects this data
- Extract information from raster
- Exports the shapefile created into PostgreSQL
- Carries out spatial calculations in PostgreSQL using Postgis including: spatial joins, calculating distance, calculating area, 
selecting points within polygon, performing intersects etc
- Importing data back into R


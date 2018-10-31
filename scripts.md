

1. Downloading automatically files of satellite based AOD products (e.g. from Earth Data\ FTP) and additional model-based predictors (e.g. from ECMWF).
2. Creating a unique grid based on the AOD product grid and the modeling aoi.
3. Extracting required sub-datasets from HDF files and converting all needed data into a table.
4. Dealing with duplicated AOD observations per day (Keeping the best quality observation\average).
5. Evaluating AOD observations and AOD cleaning. 
6. Extracting temporal variables from netCDF data.
7. Creating a table that contains all grid-days combinations and adding all required data to this table (AOD data, spatial variables, and temporal variables).
8. Joining to the PM monitors data from all variables collected  (joining by location and day).

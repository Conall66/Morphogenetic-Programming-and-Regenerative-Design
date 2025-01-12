![[ArcGIS Student Plan.png]]

- Software for visualising GIS data
## Requirements

- [x] Recommended 4 core processor
- [x] 32Gb free storage
- [ ] 32Gb RAM

## Connecting to R

library(acrgisbinding)
arc.check_product()
ArcGISFileName <- 'path'
gis_data <- arc.open(path)
Data <- arc.select(gis_data)
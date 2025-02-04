[Projecting Future Growth of Future SA Settlements](https://pta-gis-2-web1.csir.co.za/portal/sharing/rest/content/items/c08a5f6a396e4ccb9e77f6a5b722fd11/data)

## Summary

- Paper explores the methodology (without open sourced code) for 

## Key Points

### Population

- In the context of urban geography, population change (growth or decline) is an inevitable phenomenon influenced by a variety of factors. These factors can be categorised into a number of broad components posited to impact population growth patterns, including **demographic characteristics, socio-economic conditions, transportation accessibility, biophysical conditions and natural amenities, as well as policies related to land use and development, with each component having many potential influential factors** (Chi & Marcouiller, 2011; Chi & Ventura, 2011a). Spatially and temporally, population change occurs in response to changes in the influential factors at a certain location in time (Chi & Ventura, 2011b)

![[Pasted image 20250204162237.png]]
![[Pasted image 20250204162253.png]]
![[Pasted image 20250204162305.png]]
- The main components of population change are **births, deaths and migration**
- Weeks (2012) argues that internal migration can change population size and distribution at a subnational level far more rapidly than either mortality or fertility
- Chi & Marcouiller (2011) noted that the most important economic factors that influence the migration of the working age population are income and employment
- **SPECTRUM** system used to model population distribution
- Geospatial mask outlines boundaries the map can't evolve to 

![[Elevation and Slope Thresholds.png]]



### Urban Growth

- Modelling urban growth by granularising datasets: binary dasymetric modelling, three-class dasymetric modelling, globally fitted regression  modelling and locally fitted regression
- A number of authors have used **logistic regression** for modelling urban growth processes
- **Kernel-based interpolation** methods are also widely used to estimate the probability of the population distribution based on the distance to the population centre. These models allocate population based on the exponential distance decay function, using the centroid of a source zone as a control point. A window is positioned over each control point, and in turn the source zone population is allocated to grid cells falling inside the window using a unique weighting based on the distance decay function between the source zone centroid and the grid cell (Li, 2010)
- **Gravity based model**: A refined gravity model, often referred to in the literature as the IIASA methodology, was developed by the International Institute for Applied Systems Analysis (IIASA) to downscale generalised global population projections to a continuous gridded surface
- [[Problems with Gravity Method]]

## Further Information

### Greenbook
The GreenBook supports government in South Africa with adapting settlements to the impacts of climate change by providing an online repository of downscaled, baseline and future, municipal climate risk data and insights as well as adaptation information to be integrated into broader settlement planning.
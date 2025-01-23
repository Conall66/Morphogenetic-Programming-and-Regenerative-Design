[GSHL Predictive Modelling](https://human-settlement.emergency.copernicus.eu/documents/Projecting%20Global%20Population%20Grids%20to%202100.pdf)

## Methodology - Gravity Based Downscaling

| Spatial Product | Coverage | Model Application | Resolution (Spatial/Temporal) | Projection Period | Base Year      | Scenario | Units                             |
| --------------- | -------- | ----------------- | ----------------------------- | ----------------- | -------------- | -------- | --------------------------------- |
| Population      | Global   | National          | 1km/10years                   | 2020 - 2050       | 2015 (GHS-Pop) | SSP 2    | No. People                        |
| Built up Land   | Global   | National          | 1km/10years                   | 2020 - 2050       | 2014 GSHL      | SSP 2    | Portion (%) of grid cell built up |

SSP : Shared Socioeconomic Pathways

**Extract**

The spatial population data are produced by downscaling national-level aggregate
projections drawn from the Shared Socio-economic Pathways (SSPs) to 1km
grid-cells. The downscaling model developed for this work is applied at the national-
level for 240 countries and territories to produce global coverage (see Annex A for
complete list). The spatial population data are provided as gridded layers stored in
geodatabases, by world region (Figure 2), for each 10-year time step. Each 1km grid
cell contains a count of the number of persons projected to reside within that cell at
each point in time. In total, we produce four scenarios based on SSP2 (middle-of-the-
road scenario). The primary SSP2 scenario (SSP2 hereafter) assumes a spatial
pattern of population change for each country consistent with observed trends over
the period 1990-2015. The remaining three scenarios are each variants of SSP2, in
which patterns of spatial population change reflect convergence towards a specific
style of urbanization; high, medium, and low density (high, medium, and low variants
hereafter; discussed in more detail below). The starting point for these scenarios is
the observed spatial distribution of the population in 2015 at a resolution of 1 km, as
characterized by 2015 GHS-Pop data.

The 1km gridded built-up land data are also produced using a downscaling model.
However, an important distinction between the spatial population and built-up land
scenarios is that while the aggregate national-level population data used as inputs to
the downscaling model are available as part of the existing SSPs developed by the
global-change community, corresponding built-up land scenarios are not. Thus, for
this work we developed new built-up land projections at the national-level, for SSP2
and each variant, for each of the 240 countries and territories that comprise global
coverage using the same 10-year time steps. For SSP2, the projection is created by
assuming the historic relationship between national-level population change and built-
up land change in the past decades remains constant moving into the future (an
assumption consistent with the business-as-usual nature of SSP2; this process is
discussed in more detail in section 2.2.4). Similarly, for each of the variants,
convergence towards a specific style of development is assumed, in this case reflected
by the built-up per capita ratio corresponding to the high, medium, and low density
patterns of spatial population change. The spatial built-up land layers represent, at
1km resolution for each 10-year period, the portion of each grid cell that has been
developed (i.e., through man-made structures or buildings). The starting point for
these scenarios is the observed spatial distribution of the built-up land in 2014 at 1km
resolution as characterized by the 2014 GHSL data. The process of developing
each of these data products is discussed in full detail in Section 2.

## Input Data


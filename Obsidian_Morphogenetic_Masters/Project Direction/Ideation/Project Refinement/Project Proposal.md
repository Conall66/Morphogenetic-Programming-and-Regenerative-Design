## Problem Contextualisation

1. What is happening worldwide with urbanisation
2. How is it changing, and where is it changing most rapidly
3. What does this mean for major infrastructure, resource strain etc.
4. Choose one particular country (South Africa) as a case study
5. Discuss the problem of urbanisation in South Africa
6. Discuss how fringe settlements expand
7. What does this mean for fresh water supplies?
8. City planners are not working in conjunction with water infrastructure planners
9. Aim to inform policy changes (give example of where these models have previously influenced growth mechanisms)
10. Outline project proposal - building morphogenetic growth patterns of built environment

## Methodology
[[Methodology Summary]]

1. Derive relationship between water scarcity and urban morphology
	1. Morphology will be categorised into undeveloped land, residential land and built urban land, with information on the population density
	2. Water scarcity can be a percentage value (access to sanitised water by region)

		1. Determine relationship between morphology, population density and water scarcity using one way anova test (Post-hoc Turkey) or Kruskal Wallis test (Post-hoc Dunne), depending on whether the data is normally distributed
		2. Convert urban morphology data 
## Datasets
[[Datasets]]
### Assessment Criteria

1. Geospatial: Is the data offered geospatial or flat?
2. Resolution: What is the minimum accurate scale for data
3. Temporal: How far back does the data span?
4. Categories: How many types of morphology?
5. Accuracy: What is the confidence level for the data provided (look at sample sizing)
6. Data Quality: When exported, how much data cleaning will be involved?
8. Reliability: How reliable is the source?

### Morphology

| Features     | GHSL          | SA Stats                                                                                                                                                    |
| ------------ | ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Geospatial   | Yes           | No                                                                                                                                                          |
| Resolution   | Up to 100m    | Municipality - does not show actual structure                                                                                                               |
| Temporal     | Epoch 5 Years | 1994 - 2024                                                                                                                                                 |
| Categories   | Everything    | Urban town, rural village, metropolitan area, working town, farmland, fringe settlements, dense village etc.                                                |
| Accuracy     | n/a           | n/a                                                                                                                                                         |
| Data Quality |               | Seemingly 100%                                                                                                                                              |
| Link         |               | [SA Stats](https://ws.dws.gov.za/wsks/spatial_OnTrack_leaf.aspx?SubjectAreaID=1&DataTopicDetailID=3&DisplayTypeId=7&PerspectiveID=0&LvlID=10&DataTopicID=1) |
| Reliability  |               |                                                                                                                                                             |
| Notes        |               | Info on number of households, household density, number of settlements<br><br>Helpful for verification of results                                           |
#### Desired Format

| x coordinates | y coordinates | Area | cell state | year |
| ------------- | ------------- | ---- | ---------- | ---- |
|               |               |      |            |      |
 
### Population Density

| Features         | SA Stats                                                                                                                                                    | GHSL                 |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| Geospatial       | Yes                                                                                                                                                         | Yes                  |
| Resolution       | Municipality                                                                                                                                                | Up to 100$m^2$ cells |
| Temporal         | 1994 - 2024                                                                                                                                                 |                      |
| Accuracy         | n/a                                                                                                                                                         |                      |
| Data Quality     | Seemingly 100%                                                                                                                                              |                      |
| Reliability      | Gov body SA                                                                                                                                                 |                      |
| Cost             | Free, public                                                                                                                                                |                      |
| Additional Notes | Population rural/urban distribution, settlements and households                                                                                             | Shapefiles provided  |
| Link             | [SA Stats](https://ws.dws.gov.za/wsks/spatial_OnTrack_leaf.aspx?SubjectAreaID=1&DataTopicDetailID=3&DisplayTypeId=7&PerspectiveID=0&LvlID=10&DataTopicID=1) |                      |
### Water Scarcity

| Features         | DWS Drinking Water Quality                                                  | SA Stats                                                                                                                                                      |
| ---------------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Geospatial       | Yes                                                                         | Yes                                                                                                                                                           |
| Resolution       | Municipality                                                                | Municipality                                                                                                                                                  |
| Temporal         | 2018-2024                                                                   | 1994 - 2024                                                                                                                                                   |
| Accuracy         |                                                                             | Below 80% early years, 80 - 90% later years, 90 - 100% approaching 2024                                                                                       |
| Data Quality     | Seemingly 100%                                                              | Seemingly 100%                                                                                                                                                |
| Reliability      | Can not access source, seems to be SA government                            | Government body based off census data                                                                                                                         |
| Cost             | Free and public                                                             | Free and public                                                                                                                                               |
| Additional Notes |                                                                             |                                                                                                                                                               |
| Link             | [DWS Drinking Water Quality Compliance](https://www.dws.gov.za/niwis2/dwq2) | [SA Stats](https://ws.dws.gov.za/wsks/spatial_OnTrack_leaf.aspx?SubjectAreaID=2&DataTopicDetailID=77&DisplayTypeId=7&PerspectiveID=0&LvlID=10&DataTopicID=35) |
## Research

- Water consumption patterns by morphological environment and urban density
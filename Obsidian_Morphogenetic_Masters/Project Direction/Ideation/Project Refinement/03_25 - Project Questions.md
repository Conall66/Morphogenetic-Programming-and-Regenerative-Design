
## Initial Idea

Plot future SSP predictions for Cape Town evolution and map with it water scarcity [Future Global Urban Water Scarcity and Potential Solutions](https://www.nature.com/articles/s41467-021-25026-3), then create a new models showing planned water investment and potential optimised water investment (reinforcement learning model? Standard multi-variate optimisation?)
## Questions

1. Are there any other papers plotting conflicting SDGs for urban development in South Africa, using gravity based downscaling to predict morphological development?
	1. Are they looking at water scarcity specifically? Using climate models?
2. Is the code for the Greenbook report open sourced? [[SA Growth Predictions]]
	1. If not, is it worth recreating this code, or waiting for an email response from one of the authors?
	2. Which language should I work in?
3. What are the differences between gravity based downscaling and Markov-CA?
	1. Is it beneficial to implement a stochastic or deterministic approach?
	2. Is it beneficial to model the potential chaotic nature (changes in morphological trajectories)?
	3. Which modelling technique is more appropriate for population and which for urban morphology?
4. How are water and urban morphology linked to one another?
	1. How would optimising for access to water likely influence other SDGs [[UN SDGs Comparison]]?
	2. Which climate models can we use to predict water availability going forward?
	3. Are there any projects in progress right now that will increase water availability?
	4. Where should desalination plants and aquifers be situated? Will the placement of these guide urban growth?
5. How does the population distribution influence urban development?
	1. What are the different SSP scenarios?
	2. How is the population at each time step to be distributed by municipality in order to guide urban development?
	3. Does there exist a push-pull mechanism between other cities that should be modelled?
6. Who can help in this project? What research exists in modelling potential urban development outcomes?
	1. African centre for cities?
	2. C40
	3. Michael Batty
	4. Imperial urban developers (i.e. Bob)
	5. UCL/other universities urban developers
7. What are the success metrics for this project?
	1. Accuracy? (How close should results be to actual outcome - use test training and validation)
	2. Precision? (How similar should results be - probably not very with chaotic system)
	3. Time scale? (How many years into future should predictions span to serve useful)
	4. Land range? (What is encompassed within Cape Town)
	5. Model speed? (Who should be able to run the model and how quickly)
	6. Usability? (How well could urban planners use this to guide development)
	7. Optimisation? (How much to improve allocation of resources by)
	8. Novelty? (Is anyone else doing this)
8. What is the project timeline?

## Answers

1. [Peak Urban Project](https://www.africancentreforcities.net/programme/peak-urban/)
	The Peak Urban project is 

## Necessary Datasets

[[Datasets]]

- Population density by cell (dating back a minimum of 10 time steps)
- Morphological breakdown by cell (dating back a minimum of 10 time steps)
- Rainfall (dating back a minimum of 10 time steps)

## Novelty

- Linking morphological development to SDGs
- Show how densification drives wealth inequality, pushing poorer people out into the fringe settlements

## Additional Questions

- Is it better to invest in upgrading slums/fringe settlements or upgrade water infrastructure
- Why is the population in South Africa set to rise so drastically?
- South Africa loses about 37% of water through leaks - is it better to invest in repairing leaks, and if so where, rainwater/greywater treatment or to invest in new aquifers/desalination plants?


________________________________________________________________________


## Alternative Suggestions

- Reinforcement learning model governed by the same constraints (i.e. urban centres can not just emerge from nowhere - must be connected to existing infrastructure, must avoid borders, bodies of water etc.) and rewarded as it minimises transport distance, wealth inequality, water 
	- Grid based categorisation of landscape (geospatial mask for natural resources, borders etc.) with road network? topography?
	- Agents have the option to expand the city outwards, build up existing land, develop water infrastructure etc. (budget cost must be assigned per time step)
	- Penalties: infringing on natural resources, increasing travel distance, expanding into flood prone areas
	- Reward: proximity to water sources (would need existing network of water sources)
- Model optimisation for different water related investment (aquifer, desalination, piping repairs etc.) forward projection of urban development

## Additional Questions

- How does the water network in South Africa work?
	- Proximity relationship?
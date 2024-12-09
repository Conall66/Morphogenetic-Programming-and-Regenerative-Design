
[Crowd Modelling and Simulation Technologies](https://research.tees.ac.uk/ws/portalfiles/portal/6477586/Accepted_manuscript.pdf) 
## Summary

This paper gives an up-to-date account of different crowd modelling software devices and evaluates them against one-another.
## Key Points

- A major problem with many existing crowd models is that these models are too tightly coupled with some specific situations (overfitting)
### Modelling Crowd Sizes

The crowd size often determines the types of approaches used to model a crowd. For example, existing work on modelling huge-sized crowd usually treats the crowd as a whole and focuses on the global trend of the crowd, due to the tremendous computational cost involved. For a small to medium-sized crowd, the relative small size of the crowd allows researchers to model the behaviour of the individuals in the crowd. Such individual-based approaches usually build more details into the crowd model and support investigation of crowd dynamics at individual level.

An interesting fact about crowd is that crowd phenomena are in general robust to some minor differences or changes at the individual level. Secondly, the relations, particularly the social relations among the individuals, must be emphasized and properly modelled
#### 3 Criteria

1. Long time frame
2. Short time frame
3. Large crowd sizes
#### Flow Models (Large Crowd Sizes)
See [[Software List]]

- EVACNET4
- Flow Tiles
- Continuum Crowds
#### Agent Based Models
See [[Agents cells and cities]]

The decision rules for an agent are usually based on some local information that are relevant to the agent. Agents are generally **more complex** than entities (entity based models)

![[Cellular Automata Equation.png]]
mass $m$, desired velocity $v^0_i$, direction $e^0_i$, actual velocity $v_i$, time period to adapt $\tau_i$, other entities $j$, walls $w$

Entities try to increase/decrease their speed in a certain direction to meet the desired velocity over iterative periods whilst slowing down as they approach walls or other agents. The 'braking' force is defined by the f terms.

A major problem with (agents in a group sharing interest points and action points with independent Bezier curves) is that **the number of state transitions may increase quickly as more behaviours are included**. To accommodate this problem, some low level behaviours are redefined as basic building blocks such as flocking, following, attraction, splitting, etc, and the FSMs are defined only on some high level behaviours. Guided behaviour provides external control that makes it possible for the crowd behaviour to be controlled by a user or an external application.
#### Social Constraints

The modelling approach may have significant impact on the simulated crowd behaviour and also the runtime performance of the system. Thus it must be carefully chosen by a modeler. The other aspect is the behavioural factors being considered. These factors include tangible factors like physical and physiological characteristics of individuals (e.g., position, speed, etc.), and intangible factors like social factors and psychological factors (e.g., family tie, emotion, etc.).
### Evaluation Criteria

1. Flexibility: Must be able to adapt to internal or external changes (i.e. new constraints, disruptive factors etc.)
2. Extensibility: Must be able to incorporate new psychological factors
3. Execution Efficiency
4. Scalability
## Limitations

- Almost all crowd modelling software requires a high degree of computational power in order to achieve high accuracy
- Model validation: heavily dependent on the individuals involved - lack of detailed data on crowd activity
## Other Musings

- Has anyone explored a clustering approach to large crowd size models?
## Additional Reading

**Kaminka and Fridman, 2006** adopted the social comparison theory in their crowd behaviour model. **Pan, 2005** also employed a multi-agent based framework to demonstrate some emergent human social behaviours, for instance, competing, queuing, and herding.

![[Influential Research Work on Crowd Modelling and Simulation.png]]
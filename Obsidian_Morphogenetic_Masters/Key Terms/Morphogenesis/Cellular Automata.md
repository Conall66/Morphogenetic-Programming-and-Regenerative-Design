
![[Cellular Automata Equation.png]]
mass $m$, desired velocity $v^0_i$, direction $e^0_i$, actual velocity $v_i$, time period to adapt $\tau_i$, other entities $j$, walls $w$

- Entities try to increase/decrease their speed in a certain direction to meet the desired velocity over iterative periods whilst slowing down as they approach walls or other agents. The 'braking' force is defined by the f terms.
- Agents have transition matrices that determine the likelihood that they move into each neighbouring cell in cellular automata models.
- Kappa value determines the accuracy of CA model

### Moore Neighbourhoods
Extracts information on **8** neighbouring cells
### Von Neumann Neighbourhoods
Extracts information on **4** neighbouring cells
### Asynchronous vs Synchronous

- Asynchronous CA models update subsets of the data at one time, allowing for the neighbouring cells to 'react'
- Synchronous models change at once
### Fuzzy Cellular Automata

- Fuzzy states allow the cells to exist in multiple states at once (may be useful for communicating transitioning cells, or uncertainty in the results)
### Markov-Informed Cellular Automata

- Markov chains consider the previous states of the cells to determine more interesting patterns
## Advantages

- The geospatial data we have is already divided into cells
- Simple rule based transition matrix reduces computational complexity
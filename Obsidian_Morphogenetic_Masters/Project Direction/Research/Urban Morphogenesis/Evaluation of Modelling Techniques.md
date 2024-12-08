## Agent Based Modelling (ABM)

### How it Works?

### Accuracy?

### Advantages

### Disadvantages

## Machine Learning

### How it Works?

### Accuracy?

### Advantages

### Disadvantages

## Cellular Automata
[[Cellular Automata]]
### How it Works?

- Transition matrix determined by a function of neighbouring states, distance from key infrastructure (i.e. city epicentre) etc. - transition matrix can be derived from existing data for most simple model (look at probabilities cells transformed given neighbouring cells)
- Lends itself to Moore neighbourhoods given structure of cells in HSLD
### Additional Approaches

- Markov informed model takes pre-existing states
- Reinforcement learning punishes/updates transformation rules
- Integration of ABM (velocities and repulsive/attractive forces)
- Fuzziness accounts for cell uncertainty
### Accuracy?


### Advantages

### Disadvantages

## Clue-S Model

### How it Works?

### Accuracy?

### Advantages

### Disadvantages

## Comparison

| Features                | Agent Based Model | Machine Learning | Cellular Automata | Clue-S |
| ----------------------- | ----------------- | ---------------- | ----------------- | ------ |
| Short Term Accuracy     |                   |                  |                   |        |
| Long Term Accuracy      |                   |                  |                   |        |
| Computational Expense   |                   |                  |                   |        |
| Flexibility/Versatility |                   |                  |                   |        |

### Features
- Short term accuracy: how accurate is each model following one time step
- Long term accuracy: how accurate is the model as we project further into the future (100,000 steps)
- Computational expense: how computationally expensive does the model get as more data points are added?
- Flexibility/versatility: how well can the model anticipate seemingly random changes in the behaviour?
- 
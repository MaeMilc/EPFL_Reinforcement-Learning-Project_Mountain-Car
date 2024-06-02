# MP1 MountainCar MarcSchenk RominoSteiner

This project considers the Mountain Car environment, detailed in the project description (MP1_MountainCar.pdf).
Such as to find a solution to this problem statement, different reinforcement learning approaches are implemented and compared  based on their performance in the Gymnasium environment, as documented in the project description.

We implement three different agents: a Random Agent, a DQN Agent, and a Dyna Agent.

Each of our agents is implemented as a Python class and possesses the following 3 functions at least:

1. `observe(self, state, action, next state, reward)`: called whenever a new transition of the environment is observed.

2. `select action(self, state)`: picks the next action from a given state.

3. `update(self)`: performs training after each environment step


## Requirements

Running

```bash
pip install -r requirements.txt
```

installs all the libraries necessary to run the project code.

## Code

All project code can be found in `main.ipynb`.
By simply running all cells, all relevant findings can be reproduced. Note, however, that this will take several hours.

Alternatively, one can run cells seperately to produce the single plots.

Note that in any case the reproduced plots will vary slightly from the plots found in directory `report_images` or the report itself, as there were no random seeds set.

All further info can be taken from the documentation directly inside the notebook.

## Authors

- Marc Schenk<sup>1</sup>
- Romino Steiner<sup>1</sup>

1. Master in Cyber Security, ETHZ & EPFL
# Specialist-agent  

A small experimental project exploring **neuro-evolutionary computing** using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm.  
Instead of training a neural network with backpropagation, NEAT evolves both the network's weights and topology across generations. The idea is to see how an agent can learn to handle simple combat situations in a simulated environment by evolving over time.


## Overview  

The project evolves a population of agents that compete in an environment.  
Each generation, agents are evaluated based on a fitness function, and the best ones are kept, reproduced, and mutated to create the next generation.  
Over time, the networks become more specialized and develop better strategies.


## Features  

- Implements a basic NEAT algorithm from scratch  
- Evolves both weights and topology  
- Simple simulation environment (agent vs. enemies)  
- Configurable parameters for population size, mutation rate, and generations  
- Logs and visualizes fitness over time  
- Modular codebase:
  - `NEAT.py` – main algorithm logic  
  - `Controller.py` – simulation environment and agent control  
  - `NEAT_GA/` – optional extensions and experiments  


## Set up locally

### Requirements  
- Python 3.8 or higher  
- Install dependencies:  
  ```bash
  pip install numpy matplotlib

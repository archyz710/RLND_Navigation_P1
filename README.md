
# Project 1: Navigation


## Project details:
An DQN agent is trained to navigate (and collect yellow bananas) in a large square world. A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward.

1 - move backward.

2 - turn left.

3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

## Getting started:
There are three files needed to train this agent, Navigation.ipynb, dqn_agent.py and model.py. The trained weights of the DQN is saved in checkpoint.pth.

The main code, which dictate the interaction between DQN agent and the environment, is in the Navigation.ipynb. 

dqn_agent.py defines the agent class, including function to find actions with given states and update state value function (deep neural network) based on Q-learning technique. It also defines the memory space and update rule for Experience Replay.

model.py defines the deep neural network model used to approximate state-value function. 

## Instructions:
    1.Download all three files, Navigation.ipynb, dqn_agent.py and model.py

    2.Execute the codes in Navigation.ipynb 



```python

```

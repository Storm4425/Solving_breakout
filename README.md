# Solving Breakout with deep reinforcement learning: the Deep-Q-Networks (DQN) algorithm

This work is realized as coursework for the MSc Data Science at the University of Bath. 
<br>
  <br>
  

Scope:
 <br>
In recent years there have been many advances in reinforcement learning, among which the Deep-Q-Networks (DQN)
algorithm. The DQN approximates the state-value function in a Q-Learning framework with a neural network.
The scope of his project is to implement DQN
to solve the Atari game Breakout. We realise different version of the algorithm (vanilla, Double, Dueling) from the literature and 
test a new architecture that combines the Double and Dueling approaches. The game is solved successfully, with the Double and Dueling agents 
outperforming the base DQN, as reported in the literature. The Double + Dueling architecture displays a promising initial learning rate that is faster than all other implementations, however computational limitations prevent us from testing performance appropriately.
 <br>


 <br>
  
This work follows the DQN implementations of the following papers:
- [Playing Atari with Deep Reinforcement Learning](https://arxiv.org/pdf/1312.5602.pdf)
- [Deep Reinforcement Learning with Double Q-learning](https://arxiv.org/pdf/1509.06461.pdf)
- [Dueling Network Architectures for Deep Reinforcement Learning](https://arxiv.org/pdf/1511.06581.pdf)


 <br>
You can watch here the performance of the trained agents for the different variations of DQN

 <br>
 
https://user-images.githubusercontent.com/104240454/225427891-bf5d71c2-38e9-49f6-9b34-ca3fd46ead46.mp4

 <br>


 <br>
This repository contains the following files:

- main.ipynb  <br>
Models implementation and visualization of the trained agent.

- baseline_wrappers <br>
  - a number of environment wrappers taken from OpenAI baselines and adapted for this project
  - code from https://github.com/lebedov/msgpack-numpy/blob/master/msgpack_numpy.py which is used to serialize numpy arrays
  - additional supporting code

# Reinforcement-Learning-Projects

Tried different reinforcement learning algorithms to train different agents.

<h2>1- Autonumus Taxi Agent:</h2>

Implemented the Q-Learning algorithm from scratch to train the taxi agent.</br>

the agent encounters one of the 500 states (5 rows x 5 columns x 5 passanger locations x 4 destinations) and it chooses an action. </br>
Here are the possible actions: south, north, east, west, pickup, dropoff

<p align="center">
<img align="center" src="https://www.gymlibrary.dev/_images/taxi.gif" width="400"/>
</p>

When the episode starts, the taxi starts off at a random square and the passenger is at a random location. The taxi drives to the passenger’s location, picks up the passenger, drives to the passenger’s destination (another one of the four specified locations), and then drops off the passenger. Once the passenger is dropped off, the episode ends.

<h2>2- Space Invaders Agent:</h2>

Used the Deep Q-Network algorithm (DQN) from tensorflow to train the space invaders agent.

Here are the possible actions: NOOP, FIRE, RIGHT, LEFT, RIGHTFIRE, LEFTFIRE

<p align="center">
<img align="center" src="https://www.gymlibrary.dev/_images/space_invaders.gif" width="300"/>
</p>

The objective is to destroy the space invaders by shooting your laser cannon at them before they reach the Earth.

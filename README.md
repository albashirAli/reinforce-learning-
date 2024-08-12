Reinforcement Learning 

Overview & Approach: 
This Project aim is to explore and understand reinforcement learning through the use of Open AI gym environments. Specifically, I developed and tested reinforcement learning using the Q-learning algorithm with the Taxi-v3 environment. Within the environment, the agent is able to move in 6 possible directions. The six possible moves are: south, east, north, west, picking up a passenger, and dropping off a passenger. Thus each possible move resulted in a reward such that:

-1 per step unless another reward is triggered

+20 delivering passengers

-10 executing “pickup” and “drop-off” actions illegally

To achieve the best possible outcome, the agent followed an epsilon-greedy policy that balanced exploration of new actions with the exploitation of known actions based on Q-values. The Q-Value was updated using the Bellman equation, which was a culmination of reward, discount rate, and the learning data.


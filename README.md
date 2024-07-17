# Experiment-With-Learning-Policies-On-Simple-Reinforcement-Policies
Our goal will be to experiment with learning policies on simple reinforcement policies using different methods. This experment will be devided into two parts. 

#Part 1

We will consider a simple 5 × 5 gridworld problem, described below. This is the simplest abstraction of a reinforcement learning problem that allows us to benchmark and compare various learning algorithms to one another and is known as the ‘gridworld’ environment.

![image](https://github.com/user-attachments/assets/19d72840-7bc8-479a-bd35-d846579a7d1e)

Each of the 25 cells of the gridworld represent a possible state of the world. An agent in the gridworld environment can take a step up, down, left or right. If the agent attempts to step off the grid, the location of the agent remains unchanged.

The blue, green, red and yellow squares represent special states at which the behaviour of the system is as follows. At the blue square, any action yields a reward of 5 and causes the agent to jump to the red square. At the green square, any action yields a reward of 2.5 and causes the agent to jump to either the yellow square or the red square with probability 0.5.

An attempt to step off the grid yields a reward of −0.5 and any move from a white square to another white square yields a reward of 0. Intuitively, an agent with a good policy should try to find the states with a high value, and exploit the rewards available at those states.

Our Experiment Tasks For Part 1 As follows-


#Part 2

For Part 2, we will change the environment a bit by adding some terminal states represented as the black squares. This gives rise to episodes where termination occurs once the agent hits one of the black squares. We will also assume, unlike in Part 1, that any move from a white square to a white square yields a reward of -0.2.

![image](https://github.com/user-attachments/assets/9ffd4384-a787-4c7d-8c9d-c04cd5eeb0ef)

Our Experiment Tasks For Part 2 As follows-

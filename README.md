# Bangkok School of AI - Reinforcement Learning Workshop

## How to Use Notebooks

Each notebook contains the content and code-along of each session. We recommend that you run the notebooks from [Google Colaboratory](https://colab.research.google.com/) for minimal setup requirements. Edit the `Fill in The Code` section for coding assigments and check with our way of solving them in `solutions`.

## Session 1 Escaping GridWorld with Simple RL Agents
*Markov Decision Processes / Discrete States and Actions*
* What is Reinforcement Learning: Pavlov's kitties
* How Useful is Reinforcement Learning: games, robotics, ads biddings, stock trading, etc.
* Why is Reinforcement Learning Different: level of workflow automation in classes of machine learning algorithm
    * Use cases for reinforcement learning 
* Reinforcement Learning Framework and Markov Decision Processes
* GridWorld example to explain:
    * Problems: Markov decision processes, states, actions, and rewards
    * Solutions: policies, state values, (state-)action values, discount factor, optimality equations
* Words of Caution: a few reasons [Deep Reinforcement Learning Doesn't Work Yet](https://www.alexirpan.com/2018/02/14/rl-hard.html)
* Take-home Challenges:
    * Read up on Bellman's equations and find out where they hid in our workshop today.
    * What are you ideas about how we can find the policy policy?
    * Play around with Gridworld. Tweak these variables and see what happens to state and action values:
        * Expand the grid and/or add some more traps
        * Wind probability
        * Move rewards
        * Discount factor
        * Epsilon and how to decay it (or not)

## Session 2 Monte Carlo Methods
*Discrete States and Actions*
* Monte Carlo Prediction
* Monte Carlo Control: all-visit, first-visit, GLIE, constant learning rate
* Take-home Challenges:
    * Solve at least one of the following OpenAI gym environments with discrete states and actions:
        * FrozenLake-v0
        * Taxi-v2
        * Blackjack-v0
    * What are some other ways of solving reinforcement learning problems? How are they better or worse than Monte Carlo methods e.g. performance, data requirements, etc.?

## Session 3 Temporal Difference Learning
*Discrete States and Actions*
* OpenAI Gym toy environment to explain temporal difference learning: sarsa, q-learning, expected sarsa
* Homework: solve an environment with discrete states and actions such as:
    * FrozenLake-v0
    * Taxi-v2
    * Blackjack-v0
* Take-home Challenges: Solve an environment with continuous states: discretization, tile codings, etc. such as
    * Acrobat-v1
    * MountainCar-v0
    * CartPole-v0
    * LunarLander-v2
* Points to consider:
    * What are the state space, action space, and rewards of the environment?
    * What algorithms did you use to solve the environment and why?
    * How many episodes did you solve it in? Can you improve the performance? (Tweaking discount factor, learning rate, using Monte Carlo instead of TD)
    
## Session 3.5 Neural Networks in Pytorch
* Tensor operations
* Feedforward 
* Activation functions
* Losses
* Backpropagation
* Why is deeper usually better? Spiral example

## Session 4 Deep Q-learning
*Continuous States and Discrete Actions*
* Some approaches to continuous states: discretization, tile coding, other encoding, linear approximations
* Vanilla DQN: experience replay and target functions
* Take-home Challenges: Work on an Atari game and detail the process of hyperparameter tuning

## Session 4.5 Rainbow
*Continuous States and Discrete Actions*
* Rainbow
    * Vanilla DQN (experience replay + target network)
    * Double DQN
    * Prioritized experience replay
    * Dueling networks
    * Multi-step learning
    * Distributional RL
    * Noisy networks
* Take-home Challenges: Implement Rainbow and compare it to your last project

## Session 5 Policy Gradients
*Continuous States and Actions*
* Policy gradient methods: a2c, a3c, ddpg, REINFORCE

## Session 6 Multi-agent Learnig
* Monte Carlo tree search

## Other Topics
* Explore vs exploit: epsilon greedy, ucb, thompson sampling
* Reward function setting
* Hackathon nights to play Blackjack, Poker, Pommerman, boardgames and self-driving cars

## Readings
* [Sutton and Barto](http://incompleteideas.net/book/the-book-2nd.html)
* [Stanford CS234](https://web.stanford.edu/class/cs234/index.html)
* [Udacity RL Nanodegree](https://github.com/udacity/deep-reinforcement-learning)
* [David Silver Lectures](https://github.com/dalmia/David-Silver-Reinforcement-learning)
* [UC Berley Lectures](http://rail.eecs.berkeley.edu/deeprlcourse/)
* [Siraj's Move 37](https://www.theschool.ai/courses/move-37-course/)
* [Denny Britz Repo](https://github.com/dennybritz/reinforcement-learning/)
* [Intro to RL in Trading](http://www.wildml.com/2018/02/introduction-to-learning-to-trade-with-reinforcement-learning/)

## Environments
* [OpenAI Gym](https://github.com/openai/gym)
* [Unity ML-Agent Toolkit](https://github.com/Unity-Technologies/ml-agents)
* [Pommerman](https://github.com/suphoff/pommerman)
* [MetaCar](https://github.com/thibo73800/metacar)
* [Boardgame.io](https://github.com/google/boardgame.io)

## Agents
* [Unity ML-Agent Toolkit](https://github.com/Unity-Technologies/ml-agents)
* [Dopamine](https://github.com/google/dopamine)
# Deep Reinforcement Learning: Collaboration and Competition

## Environment description

In this project, we will solve the [Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment. 

This environment is **collaborative** and the goal of the **two agents** is to control rackets to bounce the ball over the net. For every bounce an agent receives a reward of 0.1. If the ball hits the ground or goes out of bounds, it receives a reward of -0.01. Thus the goal can be summarized as keeping the ball in the game for as long as possible.

The envrionment is **episodic** and the agents must receive an average score of 0.5 over 100 consecutive episodes.

### Observation and action space

The observation space is 8-dimensional and consists of the position and velocity of the ball and racket. Two actions are available to each agent, namely moving to or from the net and jumping.

# Setup

The setup was tested for Mac only. The environment can be downloaded from the following website from [this website](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip). After the download, place the zip file in the cloned git repositry and unzip it. Finally, setup a conda environment using the `requirement.txt` file in this repository.

# Training

The training is performed in the report `Report.ipynb`. The agent is contained in the file `agent.py`, the neural network in `model.py`.

# Continuous Control Project - Deep Reinforcement Learning Nanodegree

## Project Details
The repository contains a solution for the continuous control project at Udacity DRLND program. Continuous control project aims to teach how to construct reinforcement frameworks around environments with a continuous number of actions. 

As a continuous environment, we took Reacher Unity environment. In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to a position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

Two versions of the environment can be invoked:
1. The first version contains a single agent
2. The second version contains 20 identical agents, each with its copy of the environment.

The environment considered as being solved if an agent would get an average of +30 reward over 100 consecutive episodes.

Current todo list:
- [x] DDPG
- [ ] DDPG+PER
- [ ] PPO

## Getting Started

You will not need to install Unity, just install agent by following the link below:

Version 1: One (1) Agent
* Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
* Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
* Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
* Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)
  
Version 2: Twenty (20) Agents
* Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
* Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
* Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
* Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

To train the model or inference provided weights install the following python packages:

* pytorch
* unityagents
* numpy
* matplotlib

## Instructions

Since the repository provides jupyter notebooks, follow the steps of execution.
# udacity_project_reacher

## Project Details

This document is the report of the second Udacity project for reinforcment learning. 

For this project, I have trained an double-jointed arm which can move to target locations, using the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

![example reacher](images/reacher.gif)

A reward of +0.1 is provided for each step that the agent's hand is in the goal location.
Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm.
Each action is a vector with four numbers, corresponding to torque applicable to two joints.
Every entry in the action vector should be a number between -1 and 1.

I've choosen the first version of the environment with a single agent.
The task is episodic, and in order to solve the environment, the agent must get an average score of +30 over 100 consecutive episodes.

## Getting Started

Run the [Report.ipynb](Report.ipynb) which realizes the training in a Actor-Critic DDPG setup.


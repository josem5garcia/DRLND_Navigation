# DRLND_Navigation
First project of the Deep Reinforcement Learning Nano Degree

## Introduction
This repository contains all the files required in the project 'Navigation', from the Deep Reinforcement Learning Nano Degree, including all the code to run the model, and a report with the results obtained.

This project make use of the Unity environment, and creates a Deep Q-Network (DQN) agent to solve the problem implemented in Python 3 with PyTorch.

The agent has to navigate in an artificial world created by the Unity environment, in which there are yellow and blue bananas. The idea is to navigate in this world for as much time as possible, collecting the yellow ones, being rewarded with +1 if the collected banana is yellow and -1 if it is blue.

The possible actions for the agent are:
- Move forward (0)
- Move backward (1)
- Turn left (2)
- Turn right (3)

Finally, it must be highlighted that the action space has 37 dimensions, including the velocity and perception of objects in the forward direction.

## How to run the agent
In order to do this, it is just necesary to run the file 'project.ipynb', or open the Unity ML Agent with the weights included in the repository (already trained agent).

## Installing what is required
1. Install Unity (https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md)
2. Download the Unity ML environment and unzip the file (it must be pasted in the root folder).
3. Create Conda Environment with Python 3.6
4. Install Dependencies (python folder)

# Deep Reinforcement Learning Nanodegree - Project 1: Navigation

## Introduction
The problem to be solved here is to collect as many yellow bananas as possible in a 3D squared space with both yellow and blue bananas in it. This can be thought as an episodic problem in which the maximization of expected cumulative reward is sought. This can be modelled as a Q-Learning algorith:

\begin{equation}
Q(s_t, a_t) = (1 - \alpha)\cdotQ(s_t, a_t) + \alpha \cdot (r_{t+1} + \gamma \cdot \max_{a} Q(s_{t+1}, a)
\end{equation}

![\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}](https://latex.codecogs.com/svg.latex?x%3D%5Cfrac%7B-b%5Cpm%5Csqrt%7Bb%5E2-4ac%7D%7D%7B2a%7D)
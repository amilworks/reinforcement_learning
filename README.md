
# Reinforcement Learning

Machine learning has been around for decades. It can be argued that most of what we are discovering about machine learning today is actually us simply rediscovering it. Neural networks have dates that extend back to the 1950s. Perhaps the only reason they abandoned their advanced theories was because of the lack of computational power. Our iPhones today were their supercomputers yesterday. The processing power of computers today coupled to the sophisticated software we have today provides us the golden opportunity to translate and transform their theory into powerful solutions that we can use to solve "big" problems across all industries.

The approach we will explore, called _reinforcement learning_, is focused on goal-directed learning from interaction compared to other approaches to machine learning. Reinforcement learning is learning what to do to maximize a numerical reward signal. We are not told which actions to take, as in most forms of machine learning, but instead must discover which actions yield the most reward by trying them. This method requires a great deal of trial and error. If we want to be a little philosophical, we can say empiricism is invaluable here.

Reinforcement learning is defined not by characterizing learning methods, but by characterizing a learning problem. While _supervised learning_ is learning by example, reinforcement is learning by doing. 

## Example

A trash collecting robot decides whether it should enter a new room in search of more trash to collect or start trying to find its way back to its battery recharging station. How does the robot make its decision? It makes its decision based on how quickly and easily it has been able to find the recharger in the past.


## Project Abstract

In this project we will walk through a simple example--the _n_-__Armed Bandit Problem__. Imagine we are faced repeatedly with a choice among _n_ different options, or actions. After each choice, we receive a numerical reward chosen from a stationary probability distribution that depends on the action we selected. Our objective is to maximize the expected total reward over some time period, for example, over 1000 action selections, or time steps. This is the _n_-Armed Bandit Problem. 

To help us solve this problem, we will enlist the services of `Python`. 


## Inspiration and Documentation

__Google DeepDream__
* A  computer vision program created by Google which uses a convolutional neural network to find and enhance patterns in images via algorithmic pareidolia, thus creating a dream-like hallucinogenic appearance in the deliberately over-processed images

__Reinforcement Learning: An Introduction, Richard S. Sutton and Andrew G. Barto__
* Oldie but a goodie. 1998 old. Majority of inspiration. The book is divided into three parts. Part I defines the reinforcement learning problem in terms of Markov decision processes. Part II provides basic solution methods: dynamic programming, Monte Carlo methods, and temporal-difference learning. Part III presents a unified view of the solution methods and incorporates artificial neural networks, eligibility traces, and planning.

# Rl-for-satellite-control
code  used for my RL-based spacecraft attitude control research project.


# Description
Code for RL based controlled for attitude control using TD3 algorithm and fourier basis to encode state and action. It also contains OpenAI-gym style environment for simulation of dynamics.


Files included:
- envs/ADCS_gym_cont (continuous control gym env)
- envs/ADCS_gym_disc (discrete control gym env)
- train_notebook_td3.ipynb (TD3 training notebook I used. only for continuous control)


# Installation
clone down repo:
> git clone https://github.com/jakeelkins/rl-attitude-control.git


# Usage
See the two IPython notebooks  included on how to use the envs.

#Refernces
@inproceedings{inproceedings,
author = {Elkins, Jacob and Sood, Rohan and Rumpf, Clemens},
year = {2020},
month = {08},
pages = {},
title = {Adaptive Continuous Control of Spacecraft Attitude Using Deep Reinforcement Learning}
}

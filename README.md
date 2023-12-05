# DSCI 6612 - AI - Term-Project - Final-Submission

## Introduction
In this project we have applied reinforcement learning and trained a smart agent which is going to take action based on enemies actions and takes a counter action.

## Game 
Teenage Mutant Ninja Turtles - Tournament Fighters

## Game Setup
For this project we have used stable-retro librar, which is a fork of of gym-retro ('lets you turn classic video games into Gymnasium environments for reinforcement learning') with additional games, emulators and supported platforms.
Along to it we have used openCV to monitor the actions and 'stable baselines3' for modeling and training using PPO(Proximal Policy Optimization) model.

## Methods we used
We have rescaled the resolution of the game output and grayscaled the screen for faster and easy processing on local machine.

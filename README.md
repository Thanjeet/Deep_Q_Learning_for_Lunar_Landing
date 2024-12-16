# Deep_Q_Learning_for_Lunar_Landing
## Introduction

This repository implements Deep Q-Learning (DQN) to train an agent to play the Lunar Lander environment from OpenAI Gym. The agent learns to control a lander spacecraft through a series of actions to achieve a soft landing on the moon's surface.

## Code Structure

The code is divided into three parts:

### Building the AI: 
This section defines the neural network architecture using PyTorch. The network takes the state of the environment as input and outputs the optimal action for the agent to take.
### Training the AI: 
This section sets up the training loop. It defines the hyperparameters, implements experience replay, and creates the DQN agent class. The agent interacts with the environment, learns from its experiences, and updates its policy through experience replay.
### Visualizing the Results: 
This section demonstrates how to visualize the agent's performance by saving a video of the agent playing the game.

## Running the Code

### Install Dependencies: 
Make sure you have the required libraries installed, including gym, torch, numpy, etc. You can install them using pip install <package_name>.
### Train the Agent: 
Run the script to train the agent. This might take a while depending on your hardware. The script will print the average score every 100 episodes.
### Visualize the Results: 
After training, a video of the agent playing the game will be saved as video.mp4. A sample of the video of the agent playing the game is included in this repository

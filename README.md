# Colab_Compete

Project 3 for the Deep Reinforcement Learning Course on Udacity

## Environment
Each state is represented by an array with a length of 24. The environment has 2 agents which have to colaborate with eachother in order to win.

There are 2 continuous actions. They control the position of each agent and have to be between -1 and 1.

The goal of the agent is to keep hitting the ball over the net. There is a reward of +0.1 for an agent when it hits the ball over the net. Each agent has its own score an the final score for the game is the highest individual score.

The environment is considered solved, when the agent achieves an average reward of +0.5 over 100 episodes and all agents

## Getting Started
First, start off by cloning the DRLND Repository from this link: https://github.com/udacity/deep-reinforcement-learning#dependencies Follow the instructions to install the environment and all the packages needed to run the environment

Then, you need to download the environment by clicking on the link.

Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip

Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip

Windows (32-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip

Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip

Then after downloading the repository, unzip the file into the folder, making sure the file name in the second cell of reacher.ipyb matches the download

All the necessary packages except for the unity agents package are located in the requirements.txt file of this repository. The unity agents package must be installed by following the DRLND Repository installation directions

## Instructions
Open Continuous_Control.ipyb
To train the code, set the variable num_episodes in cell 7 to how long you want the agent to train. It took ~300 episodes to reach a mean score of 40 over 100 episodes. Then run the whole notebook. Once its finished training, it should save its weights and graph the agent's learning curve.

To just see the trained agent playing import the packages with the first 6 cells, then run the last cell. It will create a new Agent, load the trained weight, and have the trained agent play through a whole episode.

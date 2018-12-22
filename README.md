# Continuous Control-Deep Reinforcement Learning Nanodegree-Project 2

## Project Details
This project trains an agent to move a robotic arm within the Unity Reacher environment. The state includes 33 variables that describe how the arm is moving through space and include position, rotation, velocity, and angular velocity. Actions within the space are vectors of four numbers that describe the torque applied to the two joints of the arm and range from -1 to 1. The reward is +0.1 for every time the hand end of the arm is has reached the goal location. Since the space is continuous, the goal is to have the agent in the goal location for as long as possible. The environment is considered solved when a score of +30.0 is achieved over 100 episodes.

Note that the agent and model code in this repository is a modified version of the [DDPG-Bipedal](https://github.com/udacity/deep-reinforcement-learning/tree/master/ddpg-bipedal) implementation in the Deep Reinforcement Learning Nanodegree repository on Github.

## Getting Started

In order to run this agent, one must have Python 3, PyTorch, Unity, Jupyter Notebook, numpy, and matplotlib installed. The easiest way to set up all of the requirements and dependencies is to clone the Deep Reinforcement Learning Nanodegree repository on Github. One will need to create a new virtual environment with Python 3.6, install OpenAI gym and create a kernel with IPython. Once the notebook is open, the kernel should be selected from the kernel dropdown menu. Detailed instructions for these steps can be found on the [Deep Reinforcement Learning Nanodegree Github](https://github.com/udacity/deep-reinforcement-learning#dependencies). Finally, one would need to set up the Reacher environment by downloading the appropriate environment for one's operating system from the links below.
        
* [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
        
* [Linux (headless)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux_NoVis.zip)
        
* [Mac](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
        
* [Windows 32-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
        
* [Windows 64-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

Once the environment is downloaded, it should be put in the root directory of this cloned repository and unzipped.

To run the code, open Reacher.ipynb in Jupyter Notebook and run all cells.

# P1_Navigation_Submission

The navigation project uses RL to search for an optimal policy in the Banana environment. This environment is a 3D world in which the agent can move around and collect bananas. There are 2 types of bananas, yellow bananas which yield a reward of +1 and blue bananas which yield a reward of -1 banana. The aim is to find a policy which maximises the reward. 

## States
The state space has 37 dimensions including the velocity of the agent and some ray based perceptions in the forward direction. There are 4 dicrete actions in the action space, corresponding to moving forward and backward, and turning left and right.

## Solution
The environment is considered solved once the average reward of 100 consecutive episodes is greater than 13. 


# Installation
The jupyter notebooks are written to function on a Windows machine with a cuda enabled GPU. 

## Dependancies
First, install conda: https://www.anaconda.com/distribution/#download-section


Next, create a new conda enviornment and activate
`conda create -n Navigation python=3.6.3 anaconda`

`activate Navigation`

Now install pytorch and unity agents

`conda install pytorch=0.4.0 cuda80 -c pytorch`

`pip install mlagents==0.4.0`

Finally, the environment and scripts are downloaded from

`git clone https://github.com/SamJCKnox/P1_Navigation_Submission.git`


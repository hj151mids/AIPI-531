# AIPI-531
## Homework 1
In homework 1, I was asked to recreate one of the RL games from stable baseline 3 tutorials and recorded the training process using tensorboard as well as video.
I was then asked to explore Monte Carlo, Bootstrap, or vanilla advantage for A2C and compare performances.

## Homework 2
For regular DQN, Q is over-estimated and can slow down the training since the same actions are chosen many times. A better solution is to create a double DQN model which decouples action selection from value estimation. The two networks Q_net_target and Q_net are in charge of different jobs to avoid over-estiamtion. In Homework 2, the performances of DQN and double DQN are compared. Using double DQN, we can avoid the over-estimation of Q values.  

![image](https://user-images.githubusercontent.com/90075179/221078803-0e9624d2-e1ae-4ac0-b706-46cf13b6f4c5.png)


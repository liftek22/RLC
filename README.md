# RLC
For works of the 'RL based Control' team of UIU-NSU collaboration


We are starting by doing this Maze solver project https://www.sciencebuddies.org/science-fair-projects/project-ideas/ArtificialIntelligence_p008/artificial-intelligence/machine-learning-maze


## 18th January 2024


Reading the text. 


## 28th March 2025 

Resuming this work. 

_The computer can learn how to navigate a maze on its own.  It does so by playing the maze many times and every time it makes a mistake, it learns from it._

vs. 

*The computer can learn how to navigate ANY maze on its own.  It does so by playing the maze many times and every time it makes a mistake, it learns from it. Over time, it gets better and better at finding the right path in all kinds of mazes, without you having to tell it the steps for each maze separately.*

RL actually does the second one! So powerful. 

So the computer program is the 'agent'.  And as it moves through the maze, it iteracts with the maze, the 'environment'.  The environment responds to the agent's action indicating whether the agent has made a good move or not.  

*RL lets the computer learn from experience, like how we learn from our mistakes and get better at things over time. It's a smart way for the computer to solve many different maze puzzles efficiently without needing a special program for each one.*

Continue from 5th paragraph of 'Introduction'. 

Time spent: 0.33

## 29th March 2025

Q-learning,  is  a specific approach in RL where a machine learns to make decisions by using a table to remember which actions are best in different situations.

## 2nd April 2025 

RL is particularly helpful for situations where we want to train machines to have certain skills we do not fully understand ourselves.

'credit assignments'

Agent takes many actions before it succeeds and gets a reward. Then, everytime the agent wins, we can look back on the actions it took and slowly figure out which game states were helpful and which weren't. 


## 4th April 2025


During the abovee reflection, we are assigning values to the different game states and deciding on a policy on which action works best.  We need values and policies  to get anything done in RL. 

Policy - what action to take. 

High risk, high reward policies.  Low risk, low reward policies. 


## 5th April 2025

Suppose the robot wants to go to a destination within a gridded area.  Robot is the agent here and gridded area is the environment. Lets say he starts from (3,2) grid.  His possible actions are : go left, go right, go up , go down.  If he takes one of these actions, his state changes ( state is updated).  He can continue changing states and exploring until he reaches the destination at what point he will get a reward. 


Exploitation ( of prior knowledge) vs exploration ( of new knowledge).  

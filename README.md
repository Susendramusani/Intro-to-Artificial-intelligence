
# Introduction: #

A two-player game called Tic Tac Toe can be played on any square grid. In the zero-sum game of Tic Tac Toe, player 1's victory equals player 2's loss. Typically, it involves playing the grid and placing either X or O. Player 2 receives key O if Player 1 receives key X. A player wins if they are able to complete their key in every cell in every row, column, and diagonal.

![AI PROJECT](https://github.com/susendra143/Implementation-of-Multiple-Tic-Tac-Toe-Agents-in-a-Tournament-Setting/assets/145168825/3413783e-d5f8-4ff7-93de-73bbf16753d1)



# Algorithms used:

Four Agents have been created by us to compete with one another.

# Adversarial search Algorithms:: #

Minimax Agent

Alpha beta Minimax Agent

Expectimax Agent

Reinforcement Learning Algorithm::

Q-Learning Agent

# Minimax Algorithm:

Minimax is a backtracking algorithm that is widely used in game theory and decision making, particularly to determine the best move in two-player zero sum games. Every node in the Minimax tree representation is a game state after a certain action is taken. It features recursive layers of max and min layers, where the maximizer seeks to maximize the player's outcome and the minimizer seeks to obstruct the player's outcome.

# Alpha Beta Minimax Algorithm:

The only way this differs from Minimax is that the algorithm determines which child nodes or other game states it has to examine before returning the optimal value. The values of alpha and beta are used for this. For maximizers, Alpha has the best value, while for minimizers, Beta has the best value.

# Expectimax Algorithm:

This is comparable to Minimax as well, only instead of Minimizer, we have the chance node, which is the predicted utility and the average of all possible nodes. This algorithm assumes that the opponent's next move will depend on chance rather than that they may always play optimally.

# Q-Learning Algorithm:

The Q-Learning method is based on reinforcement learning, and at first, the agent is unaware of its surroundings. It gains rewards after playing a few games and gains knowledge about the area. Agents learn which moves are good and which are bad by earning incentives. Before being used in a competition with other players, this agent needs to be trained in a gaming environment.

# Code execution instructions:

Run the file Implementation of Multiple Tic-Tac-Toe Agents in a Tournament Setting.py

Enter agent1 and agent2 as shown in the console (without typos) and see how the agents play.

Keep an eye on the incentives and the grading system.

Run multiple times and check with multiple agents to compare which agent plays the game better.

Make sure you select 2 different agents for Tic-Tac-Toe game.

# Reference 
1. https://www.learndatasci.com/tutorials/reinforcement-q-learning-scratch-python-openai-gym/
2. https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html
3. https://www.datacamp.com/tutorial/introduction-q-learning-beginner-tutorial


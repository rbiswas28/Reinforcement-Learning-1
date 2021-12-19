# Reinforcement-Learning-1
Build an RL agent that learns to play Numerical Tic-Tac-Toe with odd numbers.You need to train your agent using Q-Learning. The environment is playing randomly 
with the agent, i.e. its strategy is to put an even number randomly in an empty cell. If your agent wins the game, it gets 10 points, if the environment wins, 
the agent loses 10 points. And if the game ends in a draw, it gets 0. Also, you want the agent to win in as few moves as possible, so for each move, it gets a -1 point.
Build the reward structure as below:

+10 if the agent wins (makes 15 points first)

-10 if the environment wins

0 if the game ends in a draw (no one is able to make 15 and the board is filled up)

-1 for each move agent takes

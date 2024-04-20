# QRL-Labyrinth-Exploration-
In this repo, there are codes and documents related to the Labyrinth Discovery game using the Quantum Reinforcement Learning method.

This Python programme represents a maze exploration game. The player tries to find a target in a maze. The maze contains walls (1) and empty spaces (0). At each step the player can move north, south, east or west. The player makes a random movement using quantum circuits and tries to reach the goal.

The main functions of the programme are:

1. `create_quantum_circuit()` function: Initially creates a quantum circuit and returns it.

2. `move(qc, action, current_row, current_col)` function: Updates the current position of the player according to a given movement command (`action`). This function allows the player to move before colliding with walls. Returns the updated position.

3. `play_game()` function: Starts the game. The player makes random moves until he reaches the goal. At each step, the player's movement, current position and number of steps are printed on the screen. When the goal is reached, a congratulatory message is displayed.

4. The programme starts the game by calling the `play_game()` function.

This programme demonstrates the use of quantum circuits in a simple game scenario. By making a random move at each step, it is possible to examine the probability of the player reaching the goal. This provides an interesting example that can be used in areas such as quantum reinforcement learning.

# QLearning_chasingTheBall
This is my first coding in Python to implement a Q-Learning technique. It is expected that the viewers are familiar about the conepts of the reinforecement learning and what are the different components like transition probabilities etc.

# Libraries used
Pygame and Numpy - supporting library

# Notes
1. Python doesn't have circle object so we created one by our own in classes.py
2. State class in a combination of circular and rectangular obejct in classes.py
3. Q is the state-action pair.
4. QIDic uses the indices of the Q table.

# Result Limitations
The bar doesn't miss the ball from the same position twice. Probably we should experiment with the learning rate in the furture, so the table gets converge very quickly.

🐍 Snake Game AI using Deep Q-Learning
This project implements an AI agent that learns to play the classic Snake game using Deep Reinforcement Learning (DQN). The agent improves its strategy by maximizing the game score (reward) through experience — no hard-coded rules!

Features:
  Deep Q-Network (DQN) agent using Keras and TensorFlow
  Self-play training via rewards and penalties
  Real-time gameplay display with Pygame
  Save/load model weights
  Training visualization with Seaborn
  Configurable hyperparameters and training settings

📊 Visualizing Training
After training, the agent’s performance is visualized using Seaborn:
  Score per episode
  Moving average
  Standard deviation
  This helps track improvements over time.


How It Works:
1. State Representation
    The agent receives a simplified representation of the game state (direction, food position, danger).
2. Action Space
    The action is one of: straight, right turn, or left turn.
3. Rewards
    +10 for eating food
    -10 for crashing
    Small reward for each step to encourage exploration
4. Neural Network
    3 Dense layers
    Trained using experience replay and epsilon-greedy policy

Example Performance:
After a few minutes of training, the agent typically:
  Learns to avoid crashing
  Strategically chases food
  Scores consistently above 30–50 points








License
MIT License — See LICENSE file for details.
Acknowledgments
Inspired by classic reinforcement learning examples and open-source contributions by the AI and game dev community.

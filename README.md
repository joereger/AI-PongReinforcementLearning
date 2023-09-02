# Teaching AI to play Pong using reinforcement learning.

## Overview
This project aims to create a Pong game using Pygame and train an agent to play it using Reinforcement Learning (RL). The agent will control one of the paddles and learn to play against a static opponent.

"Yeah, it's been done a bunch, I'm learning. Back in my day we had Pong but AI was out of reach you young punk." -- Joe Reger, Sat Sep 2, 2023 4:48PM EST

## Objectives
1. **Implement Pong Game Mechanics**: Create the basic game elements like paddles and the ball using Pygame.
2. **Define RL Elements**: Establish the state space, action space, and reward function for the RL agent.
3. **RL Algorithm**: Choose and implement an RL algorithm (e.g., Policy Gradients or DQN) to train the agent.
4. **Training**: Train the RL agent using the game environment.
5. **Evaluation**: Assess the performance of the trained agent.

## Tools Used
- **Pygame**: For game development and rendering.
- **Reinforcement Learning Algorithms**: For training the agent (e.g., Policy Gradients, DQN).

## Pygame Skills
- Animation: Moving paddles and the ball.
- Collision Detection: Identifying when the ball hits a paddle or wall.
- Event Handling: Capturing keyboard or mouse events for manual control of a paddle.

## RL Concepts
- **State Space**: The position and velocity of the ball and the position of the paddles.
- **Action Space**: Move the paddle up or down.
- **Reward Function**: Positive reward for hitting the ball, negative for missing it.

## Running the Code
The code is designed to run in a Jupyter Notebook. Pygame will open in an external window for real-time rendering and interaction.

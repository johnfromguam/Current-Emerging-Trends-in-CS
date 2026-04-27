# Current-Emerging-Trends-in-CS

## Overview
This project focuses on building an intelligent agent using deep Q-learning to solve a pathfinding problem. The goal of the agent (the pirate) is to navigate a maze and reach the treasure located in the bottom-right corner while avoiding obstacles.

This project demonstrates how reinforcement learning and neural networks can be applied to a real-world style problem where the solution is not explicitly programmed.

---

## What I was Given
I was provided with starter code that included:
- The maze environment ('TreasureMaze.py')
- The experience replay system ('GameExperience.py')
- A partially completed training function ('qtrain')
- A function to build the neural network model ('build_model')

The provided code handled the environment setup and basic structure, but the core learning logic needed to be completed.

---

## What I Implemented
I completed the deep Q-learning training process by:
- Implementing the main training loop inside the 'qtrain' function
- Adding epsilon-greedy action selection (balancing exploration and exploitation)
- Storing and replaying experiences for training
- Training the neural network using batches of past experiences.
- Tracking win/loss performance over time
- Fixing logic and runtime errors during development.

I also made adjustments to ensure the agent handled invalid actions correctly and avoided infinite loops.

---

## How It Works
The agent learns by interacting with the environment
1. It observes its current state in the maze
2. It selects an action (move up, down, left or right)
3. It receives a reward or penalty
4. It stores the experience
5. It trains the model based on past experiences

Over time, the model improves and learns the optimal path to the treasure.

---

## Key Concepts Applie
- Reinforcement Learning
- Deep Q-learning (DQN)
- Neural Networks
- Exploration vs. exploitation
- Experience Replay
- Model Training and Optimization

## Reflection

1. Computer scientists design and build systems that solve problems efficiently. In this project, I applied concepts from machine learning to create an agent that can learn from experience rather than follow hard-coded rules. This matters becaues many real-world problems are too complex to solve with traditional programming alone.

---

2. I break problems down into smaller parts and focus on understanding how each component works. In this project, I first worked on understanding the environment and the starter code before implementing the training logic. I also relied heavily on testing an debugging to identify and fix issues.

---

3. As a developer, I am responsible for ensuring that systems have reliably and do not produce harmful or unintended outcomes. In machine learning, this includes making sure models are trained properly and do not behave unpredictable. It is also important to consider how these systems may impact user and organizations.

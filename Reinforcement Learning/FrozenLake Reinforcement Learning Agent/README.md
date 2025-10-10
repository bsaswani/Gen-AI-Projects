# ❄️ FrozenLake Reinforcement Learning Agent

# 📌 Overview
The FrozenLake Reinforcement Learning Agent is designed to solve the FrozenLake-v1 environment using Q-learning. It learns to navigate the frozen lake, reach the goal, and avoid holes by updating a Q-table over multiple episodes.

# ⚙️ Workflow

1. Initialize the FrozenLake environment.

2. Set up a Q-table with zeros for all states and actions.

3. Define hyperparameters: learning rate, discount factor, and exploration rate.

4. Run the training loop using an ε-greedy policy and update the Q-table.

5. Test the trained agent by selecting the best action at each state.

# 📊 Environment

1. OpenAI Gymnasium – FrozenLake-v1

2. States: 16

3. Actions: 4

# 🛠 Technologies Used
1. Python

2. NumPy
   
3. Gymnasium
   
4. Google Colab

# 🚀 Usage
1. Open FrozenLake_RL_Agent.ipynb in Google Colab.

2. Run all cells to train the agent and observe step-by-step movements.

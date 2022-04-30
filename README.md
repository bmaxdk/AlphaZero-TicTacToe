# AlphaZero-TicTacToe
Multi-Agent Reinforcement Learning

### AlphaZero Algorithm
1. Initialize network for critic and ploicy (v_θ, π_θ).
2. Play a game using Monte-Carlo Tree Search (MCTS) for choosing moves.
3. Compute loss function, L(θ), that we can perform gradient descent to update both the policy and the critic.
4. Repeat step 2-3

# AlphaZero-TicTacToe
Multi-Agent Reinforcement Learning

### AlphaZero Algorithm
1. Initialize network for critic and ploicy (v_θ, π_θ).
2. Play a game using Monte-Carlo Tree Search (MCTS) for choosing moves.
3. Compute loss function, L(θ), that we can perform gradient descent to update both the policy and the critic.
4. Repeat step 2-3


### Howe does learning happen intuitively?
Starting from random critic and policy, the Monte-Carlo tree search in AlphaZero should be no better than a standard Monte-Carlo tree search.

### How doe is it learn?
In the beginning the critic is able to improve because whenever we reach and game during the tree search, the end game outcome is propagated in the tree and the critic will be able to predict this outcome better and better. After the critic becomes less random, the policy will start to improve as well. As training goes on, the AlphaZero agent will first learn how to play the end game very well. As the end game improves, the mid game will improve as well. Eventually, the algorithm will be able to anticipate long sequencs of expert moves, leading to an expert level of gameplay.

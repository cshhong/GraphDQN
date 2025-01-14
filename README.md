# GraphDQN: Reinforcement Learning with Graph Networks

This project explores the integration of graph neural networks into the Deep Q-Learning (DQN) framework. By leveraging the structural advantages of graph networks, we seek to use RL in complex environments.

## Architecture
- **Graph Neural Networks**:
  - Incorporates `torch_geometric` for constructing and processing graph-based data.
  - Graph observations are encoded, processed through recurrent message-passing layers, and decoded for Q-value estimation.
- **Encode-Process-Decode**:
  - Follows the framework from Battaglia et al. (2018), implementing independent graph networks for encoding and decoding and recurrent graph networks for processing.
 
## References
Battaglia et al. (2018): Relational Inductive Biases, Deep Learning, and Graph Networks arXiv:1806.01261.
Bapst et al. (2019): Structured Agents for Physical Construction arXiv:1904.03177.
Mnih et al. (2015): Human-Level Control Through Deep Reinforcement Learning.

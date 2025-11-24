
# Fuzzy multiplex Optimization

- Inputs
    - Synthetic data targets
    - A fuzzy multiplex
- Model Components and Function
    - Inner graph/FCM-like multilayer
    - ACOR (Ant Colony Optimization for continuous values) for the inner layer
    - Soft target influence for each inner FCM to target data based on outer layer
    - Interdimensional per outer-graph node layers
    - Mutual information selection and targeted evolution of the inner multilayer
    - Outer graph network layer
    - ACOR for the outer layer based on inner layer outputs
    - Update rule of the outer layer based on objectives
    - Update rule for the inner layer based on soft output targets of the outer layer
- Outputs
    - Inner FCM/graph structures tune for processes with fuzzy intervals
    - Activations for the inner per outer graph nodes and targets
    - Outer graph structure tune to objectives

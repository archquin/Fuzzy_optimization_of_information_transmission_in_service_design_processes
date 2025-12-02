
# Fuzzy multiplex Optimization

- Inputs
    - Synthetic data targets
    - A fuzzy multiplex
- Model Components and Function
    - Inner graph/FCM-like multilayer
    - Custome ODE for the inner layer
    - Nodes per inner target
    - Interdimensional per outer-graph node layers with decorelation
    - Outer graph network layer
    - Objective metrics for the refinment
    - and decorelation
    - Update rule of the outer layer based on objectives
- Outputs
    - Inner FCM/graph structures tune for processes with fuzzy intervals (FMT tensor)
    - Activations for the inner per outer graph nodes and targets
    - Outer graph structure tune to objectives
    - FMT Predictor like FCM predictor

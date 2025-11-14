# Gradient Descent — Code From Scratch

-> This project implements **Gradient Descent** from scratch for linear regression and demonstrates how the algorithm updates model parameters iteratively to minimize the loss function.  
-> It focuses on intuition, mathematics, code, and visualizations (loss curve, parameter updates, and regression-line animation).


## Objectives:-
-> Derive and implement the gradient descent update rules for slope (`m`) and intercept (`b`) in linear regression.
-> Visualize **loss vs iterations** to study convergence.
-> Observe how different **learning rates** and **initializations** affect training.
-> Build intuition about **batch gradient descent** (can be extended to SGD / mini-batch).


## Topics Covered:-
-> Mean Squared Error (MSE) loss and its gradients
-> Batch Gradient Descent update rules
-> Learning rate tuning and convergence behavior
-> Visualization of loss curve and parameter trajectories
-> Simple extension ideas: stochastic/mini-batch gradient descent, regularization


## Implementation Steps:-
1. Load a simple synthetic or real dataset (single feature for clarity).  
2. Initialize parameters `m` (slope) and `b` (intercept).  
3. For each iteration:
   -> Compute predictions `y_pred = m * x + b`
   -> Compute loss `MSE = (1/n) * sum((y - y_pred)^2)`
   -> Compute gradients:
     -> `dm = -(2/n) * sum(x * (y - y_pred))`
     -> `db = -(2/n) * sum(y - y_pred)`
   -> Update:
     -> `m = m - alpha * dm`
     -> `b = b - alpha * db`
4. Record loss and parameters at each iteration for plotting.
5. Plot loss vs iterations and show final regression line.


## Libraries Used:-
-> Python (NumPy, Pandas)
-> Matplotlib (for plots)
-> (Optional) seaborn for nicer visuals


## Things to do: 
1. **DQN:** Runs and the results obtained are the same as the expected results. 
    - Training time: 12 mins (approx.) for 500 episodes
    a. **Hyperparameter tuning:**
        - Grid search 
        - Random search

      * Hyperparameters on which search is to be performed: 
      * MEM_SIZE = 10000        (5000, 10000)
      * UPDATE_TARG_FREQ = 10   (5, 10, 15, 20, 25)
      * GAMMA = 0.99            (0.2, 0.5, 0.8, 0.9, 0.99)
      * BATCH_SIZE = 32         (8, 16, 32, 64, 128)

      * EPS_MAX = 0.9           (0.85, 0.9, 0.95)
      * EPS_DECAY = 200         (100, 200, 300)
      * EPS_MIN = 0.05          (0.02, 0.05, 0.1)

    But, training time maybe large for grid search. Solution?
  
2. **VPG:** It runs without errors but the results obtained are quite different 
   from the expected results. 
   (How to debug the neural network?)

FASHION MNIST Optimizer Comparison


This experiment compares different optimizers on the MNIST dataset to evaluate convergence speed and accuracy.
Optimizers tested: SGD, SGD with Momentum, Adagrad, Adam, RMSProp

Findings-
All models converged at around 8 epochs.

Adam and RMSProp reached ~90% accuracy fastest.

SGD with momentum showed improved stability compared to plain SGD.

Adagrad converged slower but still stabilized.

Takeaway-

Optimizer choice significantly impacts training speed and stability. Adam and RMSProp are strong defaults, while momentum improves SGD performance.
There is not much difference in convergence and accuracy between optimizers since Fashion MNIST is a small and simple dataset .All models converged 
by 8 epochs, hence differences in optimizer behaviour shrink.

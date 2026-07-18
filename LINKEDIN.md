# LinkedIn project entry

## Project title

**Restricted Boltzmann Machines on MNIST: Energy Landscapes and Contrastive Divergence**

## Project URL

https://github.com/Amir-SaiediSaber/restricted-boltzmann-machine-mnist

## Description

Implemented a Restricted Boltzmann Machine from first principles with NumPy and trained it on binarised MNIST digits using Contrastive Divergence and block Gibbs sampling. Analysed gradient convergence against the Monte Carlo noise floor, visualised learned receptive fields and generative samples, measured free-energy barriers between digit classes, and compared ten configurations across optimiser, encoding, L1 regularisation, hidden width, and CD depth. The saved experiments reveal barriers of approximately 60–100 free-energy units and strongly confined Gibbs dynamics across the tested class basins.

## Skills

Python · NumPy · Machine Learning · Restricted Boltzmann Machines · Energy-Based Models · Contrastive Divergence · Gibbs Sampling · Statistical Physics · MNIST · Data Visualization

## Short post text

I have published my Restricted Boltzmann Machine project on GitHub.

I implemented the RBM training and sampling workflow from first principles, including Contrastive Divergence, Hinton visible-bias initialisation, RMSprop, L1 regularisation, and Gibbs-chain generation. I also studied the model as an energy landscape by measuring class-to-class free-energy barriers and comparing ten hyperparameter configurations.

The most interesting result was the connection between large free-energy barriers and quasi-ergodic Gibbs behaviour: in the saved experiment, no more than 0.6% of sampled steps left their starting digit basin.

Repository: https://github.com/Amir-SaiediSaber/restricted-boltzmann-machine-mnist

#MachineLearning #EnergyBasedModels #RBM #Python #StatisticalPhysics #MNIST

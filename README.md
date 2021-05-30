# GANs for Synthetic Tabular Data Generation
Using and comparing different GAN models for synthetic tabular data generation, based on an existing dataset

Generated 50 synthetic values using Vanilla GAN, WGAN, CTGAN, and CopulaGAN.
Compared the generated datasets with existing one and measured the accuracy for each to determine which one worked best for the current data. 

CTGAN worked best for my dataset as it generated data within the existing range. The Gaussian curve generation from CopulaGAN led to negative values because a lot of rows had '0' as their value.
Some column values also got highly inflated because of this. 

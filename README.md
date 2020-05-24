# Performing-Simulations-for-Probability-Estimation

The aim here is to simulate random walks for a particle in 2-D using Brownian motion in order to estimate the probability of P(X<0|y=0 for the first time). X is a random variable and can take different values based on where the particle crosses the x-axis (y=0) for the first time. 

Also the cumulative distribution P(X<x|y=0 for the first time) is plotted by performing simulations to find the probabilities for different values of x-axis crossings. 

The simulations are performed using a for loop first. Afterwards, in order to speed up the simulations, the implementation is vectorized by getting rid of the for loop. 

# Simulation-of-Gaussian-Graphic-Model
A simulation of GGM (Gaussian Graphical Model) based on different data generating ways.

We finish the simulation of GMM (Gaussian Graphic Model) in three data generating modes, 
and we know that the differences among different data modes means the different situations of 
the **Adjacency Matrix** .

Three data modes as follows:

- Only elements on the diagonal is non-zero.

- Only elements on the diagonal and the second diagonal is non-zero.

- Uses a binomial distribution variable，a probability to make sure that the matrix is positive，and a identity diagonal matrix.

Besides, we also use a real dataset provided in the R "space" package called spaceSimu to apply the GGM.

For each data mode, we use two different statistical methods to find the estimation of the parameters.

One use the likelihood function with Penalty, which is proposed by Yuan and Lin in 2017, 
the other uses linear regression methods proposed by Meinshausen N. in 2006.

And we found that the second method performs better in our simulation.

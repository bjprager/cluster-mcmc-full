# cluster-mcmc-full
The full release of a Markov Chain Monte Carlo analysis which converts pulsar timing files into a statistical analysis of globular cluster potentials.

Included in this repository is the main suite of codes written to calculate the core density, core radius, and concentration of pulsars surrounding the core. Also provided are the distribution of de-projected pulsar positions using this method (which were sampled over using a parallel tempering technique).

This all can be accomplished using just the first order derivatives of the pulsar's spin frequency or with the first order and second order derivatives combined. (Note: Current development is being undertaken by Federico Abatte in Italy to improve the second order derivative calculation to make use of proper motions for each pulsar.)

The user may also select whether they wish to fit for perturbations to the model that test the center of gravity of the cluster. Also available is an analysis that tests for the presence of a central black hole in the system assuming it is locked to the center of gravity and using the results of Baumgardt et al. simulations.

Finally, an additional script (projected_cluster.py) is included which allows the user to calculate just the cluster properties and not the pulsar positions using the results of Anderson 1992 and Phinney 1993. These results often provide decent initial conditions for the full simulation.

# Restricted Boltzman Machine
This project focuses on building a robust digit classifier for the MNIST dataset using Restricted Boltzmann Machines (RBMs).

## Working of Boltzmann Machines
The working of Boltzmann Machine is mainly inspired by the Boltzmann Distribution which says that the current state of the system depends on the energy of the system and the temperature at which it is currently operating. Hence to implement these as Neural Networks, we use the Energy Models. The energy term was equivalent to the deviation from the actual answer. The higher the energy, the more the deviation. It has been thus important to train the model until it reaches a low-energy point. It has been obvious that such a theoretical model would suffer from the problem of local minima and result in less accurate results.

## Restricted Boltzmann Machines
A major complication in conventional Boltzmann Machines is the humongous number of computations despite the presence of a smaller number of nodes. In such a case, updating weights is time-taking because of dependent connections. To reduce this dependency, a restriction has been laid on these connections to restrict the model from having intra-layer connections.

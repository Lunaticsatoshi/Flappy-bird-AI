# Flappy-bird-AI
A good implementation of NEAT genetic Machine Learning Algorithm for playing the flappy bird game
## Made using NEAT 
NeuroEvolution of Augmenting Topologies (NEAT) is a genetic algorithm (GA) for the generation of evolving artificial neural networks (a neuroevolution technique) 

## Complexification

The networks in the initial population are the simplest possible (up to the extreme of no connections at all, leaving the input and output neurons unconnected) and the algorithm only adds new structural elements (neurons, connections). This way, the resulting networks tend to be very small.

##Working 
NEAT works with the concept of species. That is simply a subdivision of the population into several groups of individuals, called species. This subdivision is based on the dissimilarity of the individuals that is computed based on similar alignment of their genotypes as is used when doing crossover. Probability of crossing over individuals from different species is then much smaller than crossover inside species. By promoting the mating of more similar parents, the children are less likely to be much worse than the parents because the parents just were compatible.

Also, within the species, the fitness is shared among the individuals. This serves two purposes. (1) It protects individuals from mutations - when a mutation happens, the fitness would normally be low but because there is fitness sharing, the individual has time to optimize itself (the weights) to adapt to this new structural change. (2) Promotes diversity because the bigger the species, the more is the fitness shared and the less fit are the members of the species.

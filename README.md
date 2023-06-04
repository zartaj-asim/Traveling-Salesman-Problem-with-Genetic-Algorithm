# Traveling-Salesman-Problem-with-Genetic-Algorithm
Task is to implement a GA that can solve a given TSP instance.


The Traveling Salesman Problem (TSP) is a well-known optimization problem that involves finding the 
shortest possible route that visits every city exactly once and returns to the starting city. In this 
assignment, you will use a Genetic Algorithm (GA) to solve a TSP instance.
Your task is to implement a GA that can solve a given TSP instance. You should use the following steps:
 Generate an initial population of solutions. Each solution should represent a possible route 
through the cities, i.e., a permutation of the city indices.
 Evaluate the fitness of each solution. The fitness should be the total distance traveled by the 
route.
 Select the fittest individuals from the population. You should use a selection method that favors 
the fittest individuals, such as tournament selection or roulette wheel selection.
 Create new offspring by applying crossover and mutation operations to the selected individuals. 
You should use a crossover method that preserves the order of the cities, such as order 
crossover (OX) or partially mapped crossover (PMX). You should also apply mutation to the 
offspring, to introduce new variations.
 Evaluate the fitness of the new offspring.
 Replace the weakest individuals in the population with the new offspring.
 Repeat steps 3-6 until a termination condition is met, such as a maximum number of 
generations or a convergence criterion.
Your implementation should be modular, i.e., you should define separate functions for each step of the 
GA. You should also experiment with different parameter settings, such as population size, selection 
pressure, crossover rate, mutation rate, etc., to see how they affect the performance of the GA.
Your deliverables should include:
 Your source code, which should be well-documented and easy to understand.
 A report describing your implementation and the results of your experiments. The report should 
include a discussion of the parameter settings that worked best, and any insights you gained 
from the experiments.
 A demonstration of your GA running on a few example TSP instances, including the best solution 
found, the fitness value, and the running time

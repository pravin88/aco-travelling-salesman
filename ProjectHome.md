Standard ACO algorithm with an offline pheromone update is implemented to solve the ty48p asymmetric TSP problem.The Algorithms is implemented with the following parameters


Ant\_count: Numbers of ants that will be exploring the population,

Iterations: Number of generations for which ants will be searching for solutions

PheromoneConstant: The constant used as a sufficient while calculating strength of pheromone applied by an individual ant based on its tour length

DecayConstant: Strength with which pheromone decays in a path

Alpha: Pheromone strength while finding the next city

Beta: Heuristic strength while finding the next city,

Initialization: How to initialize first population, either random or with a specific city


The best solution for ry48p as published in TSP site is 14422 though I managed to reach only 15473. But considering the stochastic nature of algorithms and provided more computational space, this algorithm can even give a better solution.
Following five experiments were conducted to test the performance of the algorithm with different parameter values. All the experimental results were derived by averaging out of 20 trial runs.
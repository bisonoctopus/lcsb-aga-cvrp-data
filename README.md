# Sequence-based Diversity Measurement in Adaptive Genetic Algorithms for Optimising Ordered Problems
## Abstract
Ordered problems such as the Travelling Salesman Problem (TSP), Vehicle Routing Problem (VRP) and Job Shop Scheduling Problem (JSSP) are distinct from general problems by how the quality of the solutions are dependent on the relative positions of the genes.
In these problems, the order of the genes in the genotype has a greater contribution to the fitness of the genotype than the gene positions. 
While several sequence-wise approaches have been proposed in the literature, they consider similarities according to preceding and proceeding genes rather than whole sequences. This paper proposes a new set of sequence-based metrics for measuring population diversity for ordered problems and presents an implementation with an adaptive genetic algorithm framework. Experimental results demonstrate the superiority of our approach.

## CVRP Results
This repository contains the results from 50 runs for each of the instances from the X set of the CVRP library proposed by Uchoa et al. (2017). 

- Each CVRP problem instance is organised into directories
- Solution files for each run are stored in their relevant instance directories
- Solutions are organised with the route cost in the first row followed by each vehicle's route
- Routes are encoded with the depot represented as node 0 and customers from [1, ... , N]
- Distances are rounded to the nearest integer 

## References
Uchoa, E., Pecin, D., Pessoa, A. A., Poggi, M., Vidal, T., & Subramanian, A. (2017). New benchmark instances for the capacitated vehicle routingproblem.Eur. J. Oper. Res., 257, 845–858.
# Evolutionary_Algorithm
Solving a Bank problem using evolutionary Algorithm

The Evolutionary Algorithm 
The evolutionary algorithm is implemented as follows: 
1. Generate an initial population of p randomly generated solutions (where p is a reasonable population size discussed in lectures and in the module reading), and evaluate the fitness of everything in the population. 
2. Use the binary tournament selection twice (with replacement) to select two parents a and b. 
3. Run crossover on these parents to give 2 children, c and d. 
4. Run mutation on c and d to give two new solutions e and f. Evaluate the fitness of e and f. 
5. Run weakest replacement, first using e, then f. 
6. If a termination criterion has been reached, then stop. Otherwise return to step 2.

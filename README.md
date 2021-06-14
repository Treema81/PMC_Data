# PMC_Data

This repository contains all results obtained by Nicola Bianchessi and Emanuele Tresoldi on the dataset for the Parallel Machine Scheduling Problem with Conflicts proposed by Kowalczyk, D. and Leus, R. in Kowalczyk, D. and Leus, R. (2017). "An exact algorithm for parallel machine scheduling with conflicts". Journal of Scheduling,20(4), 355–372.

A complete description of the procedures used to find these result is reported in Bianchessi, N. and Tresoldi, E. "A stand-alone branch-and-price algorithm for identical parallel machine scheduling with conflicts". Computers and Operations Research, to appear.

A preliminary version of this paper is available at https://www.researchgate.net/publication/340899189_A_stand-alone_branch-and-price_algorithm_for_parallel_machine_scheduling_with_conflicts 

In the file containing all the results the following columns headers are used

Name: name of the instance

Machines: number of identical parallel machines 

Jobs: number of jobs

Range: maximum size of a job

Density: density of the conflict graph as percentage of maximum number of edges

DB_0: dual bound at root node (-1 if not available)

Time_0: computational time to solve the root node

DB:	final dual bound at the end of the procedure (-1 if not available)

PB:	final primal bound (feasible solution) at the end of the procedure (-1 if not available)

Gap: percentage residual MIP gap 

Time: total execution time ("Timelimit" if the process was stopped after 720 seconds)

Nodes: total number of branch and price nodes explored

Solved: 1 if the optimal solution has been found, 0 otherwise. 



Note that if an instance has been proved infeasible both DB and UB are equal to -1.

For further details on the results please write at nicola(dot)bianchessi(at)unimi(dot)it or at emanuele(dot)tresoldi(at)unimi(dot)it

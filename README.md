# vehicle-routing

A consulting project on multiple vehicle routing I did for an ecommerce startup. I am releasing a portion of the anonymized dataset and the project artifacts with permission.

This is a multi-objective optimization problem that seeks to identify optimal routes for a fleet of cargo trucks while minimizing fleet allocation and distance travelled.

The solution consists of three steps: 

1. The first step is clustering locations to identify delivery hotspots. A k-means clustering model is developed.
2. The second step deals with vehicle loading and minimizing fleet allocation to each of these clusters. This is solved through linear programming. 
3. The third step is finding optimal routes to minimize distance travelled and is based on a heuristic solution of the travelling salesman problem.


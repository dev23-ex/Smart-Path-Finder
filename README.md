# Smart-Path-Finder
Both optimality and Completeness
•	Searching is one of the computer science algorithms. We know that today’s modern computers store a lot of information. To read this information proficiently, we need very efficient searching algorithms.

•	When a search algorithm has the property of optimality, it means it is guaranteed to find the best possible solution. When a search algorithm has the property of completeness, it means that if a solution to a given problem exists, the algorithm is guaranteed to find it

•	SPF finds the best Optimal and Complete Path.

•	Smart Path Finder (using A* algorithm) calculates the distance from the start point               
            and it uses the sum of those two distances.
•	Smart Path Finder is best, as long as the heuristic does not overestimate distance,    
            SPF finds an optimal path.
•	Smart Path Finder uses the heuristic to reorder the nodes so that it’s more likely that the goal node will be encountered sooner.

ALGORITHM:
•	A * algorithm could be a looking out algorithm that searches for the shortest path between the initial and therefore the final state. it's employed in numerous applications, like maps. In maps the A* algorithm is employed to calculate the shortest distance between the supply (initial state) and therefore the destination (final state).

•	A* algorithm has three parameters:

        • g: the price of moving from the initial cell to this cell. Basically, it's the addition of all  
          the cells that are visited since exploit the primary cell.

        • h: conjointly referred to as the heuristic price, it's the calculable price of moving    
          from this cell to the ultimate cell. the particular price cannot be calculated till the   
          ultimate cell is reached. Hence, h is that the calculable price. we have a tendency 
          to should confirm that there is no over estimation of the price.
        
       • f: It is the addition of g and h. So, f = g + h
•	The method that the algorithm makes its selections is by taking the f-value under consideration. The algorithm selects the tiniest f-valued cell and moves to it cell. This method continues till the algorithm reaches its goal cell.

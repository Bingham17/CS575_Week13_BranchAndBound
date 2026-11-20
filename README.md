# CS575_Week13_BranchAndBound

The traveling salesperson problem is one of the "unsolvable" NP-complete set.  There's no fast way to solve the problem, but branch-and-bound will help a bit.  There are all sorts of tricks that you can have in your bag of tricks.

Input for this program will be the number of cities to visit, followed by the XY coordinates of each. Find the best possible tour (you can) to visit everything, coming back to the start.  Use Euclidean distance to determine the length between any two locations.  The input files will not have any more than 1000 cities.

If you disable the branch-and-bound, things will run longer.  You might not be able to get the optimal solution.  This assignment is designed to get you to think a bit.  It's an NP-Complete problem.  It's unsolvable (for large inputs).  Now what?

Print out the best solution you can find, and the order of the cities.

Here are a few test cases... in your comments for your code, include the best total distance you find for tsp300.txt...

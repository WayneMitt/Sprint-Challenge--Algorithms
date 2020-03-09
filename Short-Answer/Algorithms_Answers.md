#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) 
The code inside the while loop is O(1) and the while loop will run O(n) times.  This simplifies to O(n)


b) 
The logic inside the while loop is O(1) and the while loop will run O(log(n)) times.  This simplifies to O(log(n))
Moving up a step to the for loop, the logic inside is O(1) and the for loop will run O(n) times.  This simplifies to O(n)
For the function as a whole we then have O(log(n)) * O(n)


c)
This recursion will continue to run until bunnies == 0.  This is O(n+1) which simplifies to O(n)


## Exercise II

In order to find floor f in as few eggs dropped as possible, I would take n (number of floors) divided by 2 to find the middle story of the building and drop the first egg off what we'll call floor a.  

If the egg breaks, my next test would be halfway between floor 0 and floor a.
If the egg didn't break, my next test would be halfway between floor a and floor n.

By repeating this process, I would eventually get to a point where I would test 2 adjacent floors each with different results, which would allow me to confidently proclaim floor f as described in the problem.


The runtime complexity for this solution would be O(log(n)) because as n grows, the number of times the loop will run grows at a much slower rate

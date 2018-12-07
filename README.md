# HW2
This is my report for my implementation of the Quick Sort algorithm and the Merge Sort algorithm. <br>
Merge Sort has a complexity of n(log(n)) and a requires an additional slot of memory, Quick Sort however has a complexity of (n^2) if we choose as a pivot the largest or the smalllest element of the list. If we choose a median pivot element it have a n(log(n)) complexity. Trying to avoid the worse case scenario for Quick Sort i used a random element of the list as a pivot element<br>
To avoid having a list random generated whose elements were already better sorted for one or the other algorithm, I created 10 differents lists of n elements between 0<=n<=1000, and then measured the time it takes for the two algorithms to sort the same list with timeit. I collected the 20 values and used them to draw a plot in which i show also the average of the time it took each algorithm to sort the 10 list. <br>
<br>
![graph](https://github.com/Gohos322/HW2/blob/master/graph.png)
<br>
<br>
Even if the graph show different peak every time we execute the code, the average time remain almost constant and this show us that the Quick Sort algorithm is faster than the Merge Sorte one.

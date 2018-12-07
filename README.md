# HW2
This is my report for my implementation of the Quick Sort algorithm and the Merge Sort algorithm. <br>
Merge Sort has a complexity of n(log(n)) and a requires an additional slot of memory, Quick Sort however has a complexity of (n^2) when we choose as a pivot the largest or the smallest element of the list. If we choose a median pivot element it has a n(log(n)) complexity. Trying to avoid the worse case scenario for Quick Sort, I used a random element of the list as a pivot element.<br>
To avoid having a random generated list whose elements were already better sorted for one or the other algorithm, I created 10 differents lists of n elements between 0<=n<=1000, and then measured the time it takes for the two algorithms to sort the same list with timeit. I collected the 20 values and used them to draw a plot in which also the average of the time it took each algorithm to sort the 10 list it's shown. <br>
<br>
![graph](https://github.com/Gohos322/HW2/blob/master/graph.png)
<br>
<br>
Even if the graph shows different peak every time the code is executed, the average time remains almost constant and this shows us that the Quick Sort algorithm is faster than the Merge Sort.

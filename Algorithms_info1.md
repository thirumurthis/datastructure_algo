**Sorting, Searching, Selection**

***Sorting:***

> Slow sorts

 - Selection Sort
 - Insertion Sort
 - Shell Sort
 
 > Fast Sorts
 
   - Merge Sort
   - Quick Sort
   - Heap Sort

***Searching:***

 - Linear Search
 - Binary Search
 
 Data structure used in searching 
   
   `*Linked list*` (optimal performance)
   
   `Skip list` (randomized augmentation of linked list - better performance)
   
   `Binary tree` (better average-case performance) 
   
   - Type of binary tree
   
     - `Red black tree` (good worst-case performance)
     
     - `Splay tree` (often accessed items of a tree can be accessed faster)
        
Sample Pseudo code for determining max value in an array with value A[0...N-1]
```
max (A[0..N-1])
  x <- A[0]
  l <- A[0...N-1].length  //this can be passed as arguments too.
  for i = 1 to N-1 do
     if A[i] > x then 
        x = A[i]
  return x
```



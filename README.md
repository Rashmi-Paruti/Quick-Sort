# Quick-Sort
Sort a given set of n integer elements using Quick Sort method and compute its time 
complexity. Run the program for varied values of n> 5000 and record the time taken to sort. Plot 
a graph of the time taken versus n. The elements can be read from a file or can be generated 
using the random number generator. Demonstrate using C++/Java how the divide-and-conquer 
method works along with its time complexity analysis: worst case, average case and best case.

# ALGORITHM
1. QUICKSORT (array A, int m, int n) 
2. 1 if (n > m) 
3. 2 then 
4. 3 i ← a random index from [m,n] 
5. 4 swap A [i] with A[m] 
6. 5 o ← PARTITION (A, m, n) 
7. 6 QUICKSORT (A, m, o - 1) 
8. 7 QUICKSORT (A, o + 1, n)

# Time Complexities
Worst Case Analysis: It is the case when items are already in sorted form and we try to sort 
them again. This will takes lots of time and space. Worst Time Complexity : O(n^2)

Average Case: Generally, we assume the first element of the list as the pivot element. 
In an average Case, the number of chances to get a pivot element is equal to the number 
of items. Average Time Complexity : O(nlogn)

Best Case: In any sorting, best case is the only case in which we don't make any comparison 
between elements that is only done when we have only one element to sort. Best Time Complexity : O(nlogn)

# Space Complexity
O(n) : basic approach

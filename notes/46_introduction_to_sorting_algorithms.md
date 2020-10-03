
# Introduction to Sorting Algorithms

- The benefit of having a sorted data set can make methods
  applied have their run time reduced to o(logn), which 
  is essentially o(1).


## Bubble Sort
 - This works in a linear fashion, often going from left to right,
   while swapping values if one is greater than the other,
   and placing them in an ascending order from left to right.
 - The biggest downside to this is the number of passes required
   to completely sort an array.
### The worst case run-time is o(n^2)
 

## Selection Sort
 - Starting from the left and going to the right, we grab the smallest value
   by comparing values as we move. Once we have the smallest value in the set
   we compare it the number in first position and determine if it goes before or 
   after the value. This continues until all is sorted.

 - The worst case run-time for this is o(n^2)
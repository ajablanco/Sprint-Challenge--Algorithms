#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n): (n^3) / (n^2) 


b) O(n log n): the outer loop executes n times, and I believe the inner loop executes log n times.


c) O(n): O(1 + 1 + n)

## Exercise II
I would approach this problem similar to a binary search. 

1. I would determine how many floors there are in the building.
2. Next, I would go to the middle floor and drop an egg. 
 -If the egg breaks, I will know that I am too high so I will move to the floor that is in the middle of the bottom floor and the current floor I am on and repeat the test again.
 -If the egg does not break, I will move to the middle floor between the current floor I am at and the very top floor... and repeat the steps again
 -Once I find the highest floor before eggs inevitably start to break, I will know I have successfully returned the value of f.

Since this is identical to a binary search approach, this would have runtime complexity of O(log(n)) on average and O(n) at worst.

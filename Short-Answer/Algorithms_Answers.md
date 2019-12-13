#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) The initial while loop line (a < n \* n \* n) has complexity of O(n^3) because it is reliant on 3 n's multiplied by itself. Within the loop there is complexity O(n^2) due to the (a = a + n \* n) with 2 n's multiplied together. To hit n^3 with increments of n^2 it would take n loops, giving this a value of O(n) complexity.

b) Several lines in this are constant, however the for loop (for i in range(n)) is dependent on value n, making it O(n). The while loop (while j < n:) depends on n's value, making this O(n), in combination with the for loop the complexity of this is O(n)^2

if n = 5 output is 15
if n = 25 output is 125
if n = 200 output is 1600

c) Bunny ears is dependent on the value of bunnies. As it is decremented by 1 each time, it needs to be called n times, making this O(n).

## Exercise II

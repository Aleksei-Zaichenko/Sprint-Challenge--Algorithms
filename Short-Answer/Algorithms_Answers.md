#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)
    (n * n * n) / (n * n) = n


b) O(n log(n))
    For loop fully depends on n input, 
    while loop also depends on n input, but iterative index j increases twice through each execution


c) O (n)
    Number of recursive calls depends on size of bunnies input,
    If bunnies equals 5, bunnyEars will be called 5 times

## Exercise II
O(log n)
a recursive approach can be used to solve the problem

The function is called with f(n)
if on that floor we break an egg, we call the same function recursively with passed argument n/2, f(n/2)

base case if n <= 0 return 0
if brokenEgg = True
    return f(n/2)
else
    return f


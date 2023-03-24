# DSA

Big O Cheat Sheet
-------------------

```diff
+ --Big Os--
O(1)        Constant    - no loops
O(log N)    Logarithmic - usually searching algo have log n if they are sorted (Binary Search)
O(N)        Linear      - for loop while loop though n items
O(n log(n)) Log Linear  - Usually sorting operations
O(n^2)      Quadratic   - every element in a collection needs to be compared to every other element, two nested loops.
O(2^n)      Exponential - recursinve algo solves a problem of size N
O(n!)       Factorial   - you are adding a loop for every element
```
**(1) Iterating through half a collection is still O(n) | (2) Two separate collections: O(a + b) or O(a * b)**
```diff
+ --What causes time in a function--
Operations (+ - / *)
Comparisons (<, >, ==)
Looping (for, while)
Outside Function Call( Function() )

+ --Rule Book--
**RULE 1:** Always focus on the worst case.
**RULE 2:** Remove constants O(2 + n) -> O(n) as value of n increases the constant will not matter.
**RULE 3:** Different input should have different value. O(a + b) or O(a * b) for nested.
**RULE 4:** Drop NON-Dominant terms O(n + n^2) -> O(n^2) n doesn't matter if n increases

+ --What causes Space Complexity--
Variables
Data Structure
Functions Call
Allocations
```

![image](https://user-images.githubusercontent.com/43988314/227457825-03203c23-703a-4ae2-bdc4-b0b2226443d3.png)



# CMPS 2200 Assignment 5
## Answers

**Name:**_________________________


Place all written answers from `assignment-05.md` here for easier grading.





- **1a.**

A algrorithim that finds the largest k value where 2^k is <= n, while recursivley subtracting that value until n = 0. The algrothim is optimal for our specific situation because all coins are in denominations of 2^k. 

- **1b.**
The work is log(n) and the span is log(n)
- **2a.**

Say you have 8 dollars and the given bank has denominations of 6, 5, 3 and 1 dollars. The greedy algorithim would first choose to give you the size dollar coin. You would then have two remaining dollars and the algrotihtim would give you two additional 1 dollar coins. In this case you would be given three coins. However the optimal solution would be two coins, a 5and 3 dollar coin. This shows that in this example a greedy algorhtim would not be optimal because it takes the largest fdemonination without consideration for future operations.

- **2b.**




I would create a tree with the k[n-1] and k[n-2] values as the origninal nodes. They would then each have children of thier value and the next smallest value. by doing this we can recursivley run through the entireity of possible options. I would add bottom-up memoization by having a dictionary with the smallest possible ways of reaching each smaller number so that computations do not need to be repeated. The work and span is O(n)




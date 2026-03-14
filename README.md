This repository contains pseudocode solutions for two fundamental programming problems: finding distinct elements across sets and calculating vector orthogonality using both procedures and functions.

A. Problem 1: 
1. Given two sets of integers, find the sum of all elements that are unique to either set (elements not present in both).
2. Approach: Iterate through the first set and check if each element exists in the second set. If not, add it to the sum.
3. Repeat the process for the second set, checking against the first.
4. Data Structure used: Arrays.
5. Logic used: Nested loops for comparison and a boolean flag (found) to track occurrences.


B. Problem 2: 
1. Determine if $n$ pairs of vectors are orthogonal.
2. Two vectors are orthogonal if their dot product equals 0.

 
Algorithm Explained:
The algorithm uses a bi-directional comparison strategy
1. Compare each element of Set A against all elements of Set B. If it is not found, add it to the sum.
2. Compare each element of Set B against all elements of Set A. If it is not found, add it to the sum.

Dot Product & Orthogonality 
We calculate the product of corresponding elements and accumulate them into a single value 
It explores two ways to handle data passing:
1. The procedure part (dot_product) uses Pass-by-Reference to update the ps variable directly in the main algorithm.
2. The function part (dot_product_func) uses Return Value to pass the calculated result back to the caller.

 
 Checkpoint Criteria Met
 1. Use of Arrays
 2. Use of Nested Loops
 3. Clear Comments & Logic
 4. Comparison of Procedures and Functions

This repository contains pseudocode solutions for two fundamental programming problems: finding distinct elements across sets and calculating vector orthogonality using both procedures and functions.
📝 Problem DescriptionsProblem 1: 
Sum of Distinct ElementsGoal: Given two sets of integers, find the sum of all elements that are unique to either set (elements not present in both).
Approach: Iterate through the first set and check if each element exists in the second set. If not, add it to the sum.
Repeat the process for the second set, checking against the first.
Data Structure used: Arrays.
Logic used: Nested loops for comparison and a boolean flag (found) to track occurrences.
Problem 2: Dot Product and OrthogonalityGoal: Determine if $n$ pairs of vectors are orthogonal. Two vectors are orthogonal if their dot product equals 0.
Key Concepts:Dot Product: Calculated as +(V1_i * V2_i).
Nested Loops: The main algorithm loops through n pairs (outer loop), while the dot product calculation loops through the vector elements (inner loop).
Implementations:Procedure (dot_product): Uses Pass-by-Reference to update a variable (ps) directly.Function (dot_product_func): Uses a Return Value to pass the result back to the caller.
Algorithms Explained1. Distinct Sum AlgorithmThe algorithm ensures that if an element exists in both arrays, it is ignored, effectively calculating the symmetric difference of the two sets.
Dot Product (Procedure vs Function)Procedure Version: Ideal when you want the sub-program to modify a specific variable in the main memory.
Function Version: More modular; it treats the dot product as a mathematical value that can be used directly inside an IF statement.
 Checkpoint Criteria Met
 Use of Arrays
 Use of Nested Loops
 Clear Comments & Logic
 Comparison of Procedures and Functions

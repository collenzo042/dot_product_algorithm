Project Title: Sum of Distinct Elements from Two Sets (Using Arrays in .algo)
Description: This project implements an algorithm using .algo to find the sum of all distinct elements between two sets. Distinct elements are those that appear in only one of the two sets.
Example: Set 1 = [3, 1, 7, 9] Set 2 = [2, 4, 1, 9, 3] Distinct elements = 7, 2, 4 Output = 13
Approach:
	1	Initialize Sum = 0.
	2	Compare each element of the first array with the second array using nested loops.
	3	If the element is not found, add it to Sum.
	4	Repeat the process vice-versa for the second array.
	5	Display the final sum.
Concepts Used:
	•	Arrays
	•	Nested loops
	•	Boolean flags
	•	Call by comparison logic
Language: Algorithm (.algo pseudocode)



PROBLEM 2
# Dot Product and Orthogonal Vectors (.algo)

## Description
This project implements a dot product algorithm using both a procedure and a function in .algo.
It determines whether pairs of vectors are orthogonal (dot product = 0).

## Concepts Used
- Arrays for vector representation
- Nested loops
- Call by reference (VAR)
- Call by value (Function return)
- Procedures and Functions

## Files
- dot_product_procedure.algo
- dot_product_function.algo

## Example
Vector A = [1,2,3]
Vector B = [2,-1,0]
Dot Product = 0 → Orthogonal

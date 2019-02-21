#  Trainee Evaluation Assignments

  

##  Instructions

Use HTML5 and Javascript to complete the following tasks.

  

Use separate folders for each assignment.

Ex. `/assignment_1`

  

Create a new pull request for each questions on completion, then continue on with the rest of the questions.

##  Assignments
###  Assignment 5

Have the function AlphabetSoup(str) take the str string parameter being passed and return the string with the letters in alphabetical order (ie. hello becomes ehllo). Assume numbers and punctuation symbols will not be included in the string.

----

###  Assignment 8

Have the function ScaleBalancing(strArr) read strArr which will contain two elements, the first being the two positive integer weights on a balance scale (left and right sides) and the second element being a list of available weights as positive integers. Your goal is to determine if you can balance the scale by using the least amount of weights from the list, but using at most only 2 weights. For example: if strArr is ["[5, 9]", "[1, 2, 6, 7]"] then this means there is a balance scale with a weight of 5 on the left side and 9 on the right side. It is in fact possible to balance this scale by adding a 6 to the left side from the list of weights and adding a 2 to the right side. Both scales will now equal 11 and they are perfectly balanced. Your program should return a comma separated string of the weights that were used from the list in ascending order, so for this example your program should return the string 2,6.

  

There will only ever be one unique solution and the list of available weights will not be empty. It is also possible to add two weights to only one side of the scale to balance it. If it is not possible to balance the scale then your program should return the string `not possible`.

  

Sample test cases:

```
Input:"[3, 4]", "[1, 2, 7, 7]"
Output:"Left: 1 | Right: 0"

Input:"[13, 4]", "[1, 2, 3, 6, 14]"
Output:"Left: 0 | Right: 3,6"

Input: "[5, 5]", "[1, 2, 3]"
Output: "Equals"
```

  

---
###  Assignment 10

Have the function MaximalSquare(strArr) take the strArr parameter being passed which will be a 2D matrix of 0 and 1's, and determine the area of the largest square submatrix that contains all 1's. A square submatrix is one of equal width and height, and your program should return the area of the largest submatrix that contains only 1's. For example: if strArr is ["10100", "10111", "11111", "10010"] then this looks like the following matrix:

```
1 0 1 0 0
1 0 1 1 1
1 1 1 1 1
1 0 0 1 0
```

  

For the input above, you can see the bolded 1's create the largest square submatrix of size 2x2, so your program should return the area which is 4. You can assume the input will not be empty.

  

Sample test cases:

```
Input:"0111", "1111", "1111", "1111"
Output:9  

Input:"0111", "1101", "0111"
Output:1
```

---

###  Assignment 12

  

Given a dollar amount between 0.00 and 999,999.00, create a program that will provide a worded representation of a dollar amount on a check.

  

You will be given one line, the dollar amount as a float or integer. It can be as follows:

```
400120.0
400120.00
400120
```

This will be what you would write on a check for the dollar amount.

  

```
Four hundred thousand, one hundred twenty dollars and zero cents.
```
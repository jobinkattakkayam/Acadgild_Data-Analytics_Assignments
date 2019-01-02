# Acadgild_Data-Analytics_Assignments
Data Analytics


SESSION 1: INTRODUCTION

Assignment 1.1

 
Problem Statement

1. Please mention true or false for the below statements:

a)	Prescriptive Analytics is used to predict the future outcomes 

b)	Base R packages are installed automatically 

2. What is Recycling of elements in a vector?

3. Give an example of recycling of elements.

ANSWERS

a) True

b)	False

2. Answer:     

Recycling occurs when vector arithmetic is performed on multiple vectors of different sizes. R takes the shorter vector and repeats them until it becomes long enough to match the longer one.
When applying an operation to two vectors that requires them to be the same length, R automatically recycles, or repeats, elements of the shorter one, until it is long enough to match the longer Vector. 

3.Answer 

Example 1:

Suppose we have two Vectors c(1,2,4) , c(6,0,9,10,13), where the first one is shorter with only 3 elements. Now if we sum these two, we will get a warning message as follows.
> c(1,2,4) + c(6,0,9,10,13)
[1]  7  2 13 11 15
Warning message:
In c(1, 2, 4) + c(6, 0, 9, 10, 13) :  longer object length is not a multiple of shorter object length

Here R , Sum those Vectors by Recycling or repeating the elements in shorter one, until it is long enough to match the longer one as follows..

> c(1,2,4,1,2) + c(6,0,9,10,13)
[1]  7  2 13 11 15




 



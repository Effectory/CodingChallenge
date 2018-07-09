# CodingChallenge
If you are landing on this page you are considering taking an interview for a developer position at Effectory, or are in the interview process. That's great! 

To get a bit of a gist of how you think, program and solve problems we have a small code challange for you. Hope you have fun with it!

# Counting bits
Given an integer, n, we want to know the following:
1. How many 1-bits are in its binary representation?
2. Let's say n's binary representation has k significant bits indexed from 1 to k. What are the respective positions (i.e., in ascending order) of each 1-bit?
3. The performance is really important in this challenge.


### Example

Complete Count function in PositiveBitCounter class. It has one parameter: an integer, n. It must return an integer enumerable with the following 1 + k values:
* The first index (0) must contain the total number of 1 bits in n's binary representation.
* The subsequent indices must contain the respective positions of the one-indexed 1-bits in n's binary representation.

### Output format

Return an enumerable of integers where the first element is the total number of 1-bits in n's binary representation and the subsequent elements are the respective one-indexed locations of each 1-bit from most to least significant.

### Language

You can use either TypeScript/JavaScript or C# to complete this challenge. Make sure there are no compilation/(ts)lint errors. Write clear code and use comments wherever you deem it necessary.

In the case of JavaScript/TypeScript submit a webpage with an input and a button to process the number. In the case of C# you can either create it as a WebAPI with a single call or a console application.


### Tips

The integer n = 161 converts to binary.

1 | 0 | 1 | 0 | 0 | 0 | 0 | 1
---|---|---|---|---|---|---| ---|

Reverse the binary representation.

1 | 0 | 0 | 0 | 0 | 1 | 0 | 1
---|---|---|---|---|---|---| ---|

Count number of positive bits: 3
Search the position: 0, 5, 7
Return { 3, 0, 5, 7 }

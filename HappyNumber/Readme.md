# Happy Number

# Introduction

A happy number is a number defined by the following process:

 - Starting with any positive integer, replace the number by the sum of the squares of its digits.
 - Repeat the process until the number equals 1 (where it will stay), or it loops endlessly in a cycle which does not include 1.
 - Those numbers for which this process ends in 1 are happy.
 
 Example 1:

Input:<br> n = 19 <br>
<br>
Output:<br> true <br>
<br>
Explanation: <br>
1<sup>2</sup> + 9<sup>2</sup> = 82 <br>
8<sup>2</sup> + 2<sup>2</sup> = 68 <br>
6<sup>2</sup> + 8<sup>2</sup> = 100 <br>
1<sup>2</sup> + 0<sup>2</sup> + 0<sup>2</sup> = 1 


## References

[1] [Check whether a number is happy](https://leetcode.com/problems/happy-number/)

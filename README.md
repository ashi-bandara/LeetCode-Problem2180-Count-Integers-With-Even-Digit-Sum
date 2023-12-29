
# LeetCode Challenge D15
## Achievements
[![image.png](https://i.postimg.cc/d35HVnqs/image.png)](https://postimg.cc/0KJdtYMF)

This solution outperformed 89.23% of Java users on LeetCode according to runtime metrics.


## Overview

Welcome to my LeetCode solution repository! This project addresses the coding challenge presented by [2180.  Count Integers With Even Digit Sum](https://leetcode.com/problems/count-integers-with-even-digit-sum/). Below, you'll find details about the problem, my approach to solving it, and the implemented solution.

## Problem Statement
Given a positive integer  `num`, return  _the number of positive integers  *less than or equal to*_  `num`  _whose digit sums are  *even*_.

The  *digit sum*  of a positive integer is the sum of all its digits.


**Example**

> **Input:** num = 4
> **Output:** 2
> **Explanation:** The only integers less than or equal to 4 whose digit sums are even are 2 and 4.

**Language Used**
> Java

**Difficulty**
> Easy

## Solution Overview
### `countEven(int num)` Method
Counts and returns the number of positive integers with even digit sums up to the given `num`. Iterates through the range from 1 to `num`, leveraging the `sum` method to calculate digit sums and increments a counter for even sums.

### `sum(int num)` Method
Calculates and returns the digit sum of a given positive integer. Iterates through each digit in the number, extracting digits using modulo and division operations, and accumulates the sum.

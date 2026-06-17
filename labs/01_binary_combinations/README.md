# Lab 01 — Binary Combinations

## Problem
Find all 12-bit binary numbers and count combinations
split across three groups of bits (5, 4, 3).

## Parameters
| Parameter        | Value  |
|------------------|--------|
| bit_count        | 12     |
| group_1          | 5 bits |
| group_2          | 4 bits |
| group_3          | 3 bits |

## Formula
C(n; k1, k2, k3) = n! / (k1! * k2! * k3!)
= 12! / (5! * 4! * 3!) = 27720

## Result
Total combinations: 27720

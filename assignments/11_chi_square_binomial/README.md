# Assignment 11 — Chi-Square Goodness-of-Fit: Binomial

## Problem
Test whether simulated data follows a Binomial(n=10, p=0.6) distribution
using the Chi-square goodness-of-fit test.

## Parameters
| Parameter          | Value |
|--------------------|-------|
| sample_size (n)    | 30    |
| p(A)               | 0.60  |
| p(B)               | 0.40  |
| significance_level | 0.05  |

## Formula
χ² = Σ (Nj - NPj)² / NPj

## Result
| Statistic          | Value         |
|--------------------|---------------|
| χ² statistic       | 10.71         |
| degrees of freedom | 10            |
| critical value     | 18.31         |
| decision           | H not rejected — data fits Binomial(10, 0.6) |

# Assignment 01 — Grid Path Combinatorics

## Problem
Count the number of shortest paths on a grid of given width and height,
moving only right or down.

## Approach
Pascal's Triangle — each cell equals the sum of the cell above 
and the cell to the left.
The answer sits at position (height, width) of the triangle.

## Formula
C(n, k) = n! / (k! * (n-k)!)
where n = total_steps = width + height - 2
      k = width - 1

## Example
grid_width = 6, grid_height = 4
total_steps = 8, path_count = C(8, 2) = 56

# Integer Division Bug in Swift Average Calculation

This repository demonstrates a common integer division bug in Swift when calculating the average of an array of Doubles. The bug occurs when the sum of numbers and the count of numbers are not compatible to result in a whole number.  The solution involves explicit type casting to ensure floating-point division.

## Bug

The `calculateAverage` function in `bug.swift` uses integer division, leading to incorrect results when the average isn't a whole number.

## Solution

The `calculateAverageFixed` function in `bugSolution.swift` demonstrates the correct way to calculate the average using floating-point division. 
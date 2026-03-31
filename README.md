# CS3339hw2
Homework 2: Binary Representation, Floating-point Math and Bit Manipulation
This program checks for floating point overflow. It takes two inputs as positive floating-point values, and
determines whether overflow occurs.

we are looking for the smallest number such that the computer thinks that: x + increment = x

My code doesn't require much set up
Compile: g++ -std=c++17 cs3339hw3.cpp -o cs3339hw3
When running make sure to enter your two inputs like this (without the square brackets):
./cs3339hw3 [loop bound] [increment]
accepted formats, for example:
Decimal: ./cs3339hw3 1.23 1
Scientific notation: 0.123e+01 1

To my knowledge there are no known bugs or limitations with my code.

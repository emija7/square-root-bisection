# Square Root Finder using Bisection Method 

This is a Python program that estimates the square root of a number using the **bisection method** — a classic algorithm based on binary search.

Built as part of the **Scientific Computing with Python** certification from [freeCodeCamp](https://www.freecodecamp.org/).

---

## Overview

This program demonstrates how to:
- Use **list comprehensions** and **loops**
- Implement the **bisection method**
- Work with **approximation and tolerance**
- Handle edge cases like `0`, `1`, and negative input

---

##  How It Works

The algorithm:
1. Starts with a range of values (`low` and `high`)
2. Calculates the midpoint (`mid`)
3. Squares the midpoint and checks how close it is to the target number
4. If it’s close enough (within a small tolerance), it's accepted as the square root
5. Otherwise, it adjusts the range and repeats

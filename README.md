# coding-agent-test

A simple Java project demonstrating a binary search algorithm.

## Overview

This project contains a `Main` class with a `binarySearch` method that searches for a target value in a sorted integer array and returns its index, or `-1` if the target is not found.

## Requirements

- Java 8 or higher

## Usage

Compile and run the program from the `src` directory:

```bash
cd src
javac Main.java
java Main <array elements> <target value>
```

The last argument is treated as the target value, and all preceding arguments are the sorted array elements.

### Example

```bash
java Main 1 2 3 4 5 5
```

This searches for `5` in the array `[1, 2, 3, 4, 5]` and prints the result index.

## Project Structure

```
src/
  Main.java   # Binary search implementation and entry point
```

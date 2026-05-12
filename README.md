# coding-agent-test

A Java project demonstrating a binary search algorithm implementation.

## Overview

This project contains a `Main` class with a `binarySearch` method that searches for a target value in a sorted integer array and returns its index, or `-1` if the value is not found.

## Requirements

- Java Development Kit (JDK) 8 or higher

## Build

Compile the source file from the project root:

```bash
javac src/Main.java
```

## Usage

Run the program by passing the array elements followed by the target value as command-line arguments:

```bash
java -cp src Main <array elements> <target value>
```

### Example

Search for the value `3` in the sorted array `[1, 2, 3, 4, 5]`:

```bash
java -cp src Main 1 2 3 4 5 3
```

**Output:**
```
Result index: 2
```

If the target is not found, the program prints:
```
Result index: -1
```

## Project Structure

```
coding-agent-test/
└── src/
    └── Main.java   # Binary search implementation and entry point
```

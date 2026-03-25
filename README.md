# coding-agent-test

A Java project demonstrating a binary search algorithm.

## Overview

This project contains a `Main` class with a binary search implementation that searches for a target value in a sorted integer array.

## Usage

Compile and run the program by providing a sorted list of integers followed by the target value as command-line arguments.

```bash
# Compile
javac src/Main.java -d out

# Run
java -cp out Main 1 2 3 4 5 5
```

The last argument is the target value to search for. All preceding arguments are treated as the sorted array elements.

**Example output:**
```
Result index: 4
```

Returns `-1` if the target value is not found in the array.

## Project Structure

```
src/
  Main.java   # Binary search implementation and entry point
```

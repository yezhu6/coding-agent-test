# coding-agent-test

A Java project containing a binary search implementation.

## Overview

This project implements a binary search algorithm in Java. Given a sorted array and a target value, the program returns the index of the target in the array, or `-1` if not found.

## Requirements

- Java Development Kit (JDK) 8 or later

## Build

Compile the source file:

```bash
javac src/Main.java
```

## Usage

Run the program by passing the sorted array elements as the first arguments, with the target value as the **last** argument:

```bash
java -cp src Main <array elements...> <target value>
```

**Example:**

```bash
java -cp src Main 1 2 3 4 5 5
```

This searches for the target value `5` in the sorted array `[1, 2, 3, 4, 5]` (all arguments except the last) and prints the result index.

## Output

```
Result index: 4
```

Returns `-1` if the target is not found in the array.

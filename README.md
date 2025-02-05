# Ada Off-by-one Error Example

This repository demonstrates a common off-by-one error in Ada programming related to array iteration.  The provided code contains an error that causes incorrect results and potential runtime exceptions.

## Problem Description
The `Example` procedure intends to increment each element of the `My_Arr` array. However, a subtle error leads to unexpected behavior or exceptions if the array size changes.  While this example is small, it highlights a bug pattern common to larger systems.

## Solution
The solution clarifies the array bounds to prevent the off-by-one error and ensure the loop correctly iterates over each element of the array.

## Running the Code
To run the code, you'll need an Ada compiler (like GNAT). Compile and run the provided Ada files.
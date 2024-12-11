# Go Array Index Out of Bounds Error

This repository demonstrates a common error in Go: accessing an array element using an index that is out of bounds.  The provided code attempts to write to index 10 of a 10-element array (valid indices are 0-9), resulting in a runtime panic.

The solution demonstrates how to correctly iterate within the valid index range of the array.

## How to reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run the command `go run bug.go`.

You will observe a runtime error indicating an out-of-bounds array access.

## Solution

The solution file demonstrates how to fix the error by correctly iterating up to, but not including, the upper limit of the array index.
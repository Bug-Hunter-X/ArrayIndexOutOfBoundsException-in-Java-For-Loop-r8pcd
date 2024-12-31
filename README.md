# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common off-by-one error in Java that leads to an `ArrayIndexOutOfBoundsException`. The `bug.java` file contains the erroneous code, while `bugSolution.java` provides the corrected version.

The error arises from an incorrect loop condition in the code that attempts to access an element beyond the array's valid index range. The solution shows how to fix this error with a simple change in the loop condition.

## How to Reproduce

1. Clone this repository.
2. Compile `bug.java` using a Java compiler (e.g., `javac bug.java`).
3. Run `bug.java` (e.g., `java bug`). You'll observe an `ArrayIndexOutOfBoundsException`.
4. Compile and run `bugSolution.java` to see the corrected output.

## Lesson

This example highlights the importance of careful attention to array indexing in programming.  Always double-check your loop conditions to ensure they do not try to access indices outside the valid range of the array.
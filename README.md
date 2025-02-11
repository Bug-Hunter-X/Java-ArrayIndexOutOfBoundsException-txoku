# Java ArrayIndexOutOfBoundsException Bug
This repository demonstrates a common bug in Java: an ArrayIndexOutOfBoundsException caused by an incorrect loop condition.

## Bug Description
The `bug.java` file contains a Java program that attempts to iterate through an array using a for loop. However, the loop condition `i <= arr.length` causes an `ArrayIndexOutOfBoundsException` because the valid indices of an array range from 0 to `arr.length -1`.

## Bug Solution
The `bugSolution.java` file provides a corrected version of the code. It changes the loop condition to `i < arr.length`, preventing the exception.

## How to run the code:
1. Clone this repository.
2. Navigate to the cloned directory using the command line.
3. Compile the code: `javac *.java`
4. Run the code: `java MyClass`
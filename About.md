# Recursion
Recursion in Java
What is Recursion?

Recursion is a programming technique in which a method calls itself to solve a problem. A recursive method breaks a problem into smaller subproblems until it reaches a base case, which stops the recursion.

Key Components of Recursion
Base Case – The condition that stops the recursive calls.
Recursive Call – The method calls itself with a smaller or simpler input.

**Advantages of Recursion
Makes code shorter and cleaner.
Useful for tree and graph traversals.
Simplifies problems that can be divided into smaller subproblems.
Easier to implement divide-and-conquer algorithms.
Disadvantages of Recursion
Uses more memory due to function call stack.
Can be slower than iterative solutions.
May cause StackOverflowError if recursion depth is too large.
Sometimes harder to debug.
Recursion vs Iteration
Feature	Recursion	Iteration
Method Calls	Calls itself	Uses loops
Memory Usage	Higher	Lower
Speed	Generally slower	Generally faster
Readability	Better for complex problems	Better for simple repetitions
Applications of Recursion
Factorial calculation
Fibonacci series
Binary Search
Tree Traversal
Graph Algorithms
Backtracking Problems
Divide and Conquer Algorithms (Merge Sort, Quick Sort)
Interview Questions
Q1. What is recursion?

Recursion is a process where a method calls itself to solve a smaller instance of the same problem.

Q2. What is a base case?

A base case is a condition that stops the recursive calls and prevents infinite recursion.

Q3. What happens if there is no base case?

The program continues calling itself indefinitely and eventually throws a StackOverflowError.

Q4. Is recursion better than loops?

Not always. Recursion provides cleaner solutions for certain problems, but loops are generally more memory-efficient.

Q5. Can every recursive problem be solved iteratively?

Yes, every recursive solution can be converted into an iterative one using loops and, if necessary, an explicit stack.

Conclusion

Recursion is a powerful programming concept where a method repeatedly calls itself until a base condition is met. It is especially useful for solving problems that can be divided into smaller, similar subproblems.**

Recursion is a technique in which a method calls itself to solve a problem.
1.FACTORIAL
Base Case: The factorial method has a base case where if n is 0, it returns 1. This prevents infinite recursion and serves as the stopping condition.
Recursive Case: The method computes the factorial by multiplying the current number n with the factorial of n-1, effectively breaking the problem into smaller instances of itself.
Execution Flow: Starting with n=5, the method calls itself with decreasing values of n until the base case is reached. The results are then multiplied as the stack "unwinds" to produce the final result.
2.FIBONACCI
Recursion is used here to generate the Fibonacci sequence, a series in which each number is the sum of the two preceding ones.
Base Cases: If n is 0 or 1, the method returns n. This provides stopping conditions for the recursion.
Recursive Case: For values of n > 1, the method adds the result of fibonacci(n-1) and fibonacci(n-2).
Execution Flow: Starting with n=10, the method recursively calculates each term in the sequence up to n, storing results as the recursion "unwinds."

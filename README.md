# Unexpected Behavior when Modifying Instance Variables Indirectly in Ruby

This example demonstrates an uncommon error in Ruby related to how instance variables are handled when using getter methods.  Attempting to modify the instance variable indirectly through a getter method will not update the instance variable itself. The example shows the unexpected behavior and offers a solution.

## How to Reproduce
1. Clone the repository.
2. Run `ruby bug.rb`.
3. Observe the unexpected output.  The `value=` assignment does not modify the instance variable.

## Solution
The `bugSolution.rb` file demonstrates a corrected approach.   It shows how to use an explicit setter method to correctly update the instance variable.
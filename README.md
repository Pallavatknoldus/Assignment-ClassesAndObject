# Assignment-ClassesAndObject

## Implementation of Integer Class for Integers with isPositive and negate methods and Unit Test cases.

### Write an implementation Integer of integer numbers.

The implementation should support all operations of class Nat while adding two methods:

### def isPositive: Boolean
### def negate: Integer

The first method should return true if the number is positive. The second method should negate the number. 
Do not use any of Scala’s standard numeric classes in your implementation. (Hint: There are two possible ways to implement Integer. 
One can either make use of the existing implementation of Nat, representing an integer as a  natural number and a sign. 
Or one can generalize the given implementation of Nat to  Integer, using the three subclasses Zero for 0, Succ for positive numbers, 
and Pred for negative numbers.)

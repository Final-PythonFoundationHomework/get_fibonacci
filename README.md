# Fibonacci

Objective: The objective of this exercise is to write a function that calculates the nth Fibonacci number.

## Instructions

1. Fork this repository.
2. Clone your fork.
3. Activate github actions on your fork.
4. Add secret key.

## Fibonacci sequence
The sequence follows the rule that each number is equal to the sum of the preceding two numbers. The Fibonacci sequence begins with the following 14 integers: `0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233 ...` Each number, starting with the third, adheres to the prescribed formula.

## Problem statement

Define a function `get_fibonacci_number(n)` that takes an integer `n` and returns the nth Fibonacci number. The fibonacci sequence is defined as follows:

```
F(0) = 0
F(1) = 1
F(n) = F(n-1) + F(n-2)
```

```python
def get_fibonacci_number(n: int) -> int:
    """
    Returns the nth Fibonacci number.
    args:
        n: The index of the Fibonacci number to return.
    returns:
        The nth Fibonacci number.
    """
    pass
```

## Examples

```python

>>> get_fibonacci_number(3) # 1
>>> get_fibonacci_number(4) # 2
>>> get_fibonacci_number(5) # 3
>>> get_fibonacci_number(6) # 5
>>> get_fibonacci_number(7) # 8

```

## Notes

- the function should return `0` if `n` is `0`
- the function should return `1` if `n` is `1`
- the function should return `None` if `n` is negative

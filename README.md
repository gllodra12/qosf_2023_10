# Grover's algorithm

In this repository, you'll find the solution for Task 1 of the QC Mentorship Program - Cohort 8.

## Task 1: Find prime numbers

Given a positive integer and a list of prime numbers, look for th two prime numbers, that sum the positive number. Consider an appropriate number of qubits and explain why your proposal is valid for all kinds of numbers in case.

```python
def find_the_primes_numbers(num: int, prime_list: list[int]):
    """
    num: integer value that is the positive number to decompose
    prime_list: integer list that has two prime numbers to add to obtain num

    Returns: num_1 and num_2 from prime_list that add to num
    """
```

Example:

```python
sol = find_the_primes_numbers(18,[2,3,5,7,11,13])
print(sol)
> 5,13
```

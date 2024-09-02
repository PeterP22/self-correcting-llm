# Self-Correcting LLM Coding Workflow Results

## Initial Query
```
Check if a number is prime
```

## Attempts
### Attempt 1/2
#### Generated Function
```python
def is_prime(n):
    """Check if a number n is prime."""
    if n <= 1:
        return False
    if n <= 3:
        return True
    if n % 2 == 0 or n % 3 == 0:
        return False
    
    i = 5
    while i * i <= n:
        if n % i == 0 or n % (i + 2) == 0:
            return False
        i += 6
    
    return True

# Example usage
number = 29
if is_prime(number):
    print(f"{number} is a prime number.")
else:
    print(f"{number} is not a prime number.")

# Test case
assert is_prime(29) == True, "Test case 1 failed"
assert is_prime(15) == False, "Test case 2 failed"
assert is_prime(2) == True, "Test case 3 failed"
assert is_prime(1) == False, "Test case 4 failed"

print("All test cases passed.")
```

#### Test Case
```python

```

#### Example Usage
```python
def is_prime(n):
    """Check if a number n is prime."""
    if n <= 1:
        return False
    if n <= 3:
        return True
    if n % 2 == 0 or n % 3 == 0:
        return False
    
    i = 5
    while i * i <= n:
        if n % i == 0 or n % (i + 2) == 0:
            return False
        i += 6
    
    return True

# Example usage
number = 29
if is_prime(number):
    print(f"{number} is a prime number.")
else:
    print(f"{number} is not a prime number.")

# Test case
assert is_prime(29) == True, "Test case 1 failed"
assert is_prime(15) == False, "Test case 2 failed"
assert is_prime(2) == True, "Test case 3 failed"
assert is_prime(1) == False, "Test case 4 failed"

print("All test cases passed.")
```

## Final Results
### Success: Function passed all tests
#### Final Function
```python
def is_prime(n):
    """Check if a number n is prime."""
    if n <= 1:
        return False
    if n <= 3:
        return True
    if n % 2 == 0 or n % 3 == 0:
        return False
    
    i = 5
    while i * i <= n:
        if n % i == 0 or n % (i + 2) == 0:
            return False
        i += 6
    
    return True

# Example usage
number = 29
if is_prime(number):
    print(f"{number} is a prime number.")
else:
    print(f"{number} is not a prime number.")

# Test case
assert is_prime(29) == True, "Test case 1 failed"
assert is_prime(15) == False, "Test case 2 failed"
assert is_prime(2) == True, "Test case 3 failed"
assert is_prime(1) == False, "Test case 4 failed"

print("All test cases passed.")
```

#### Example Usage
```python
def is_prime(n):
    """Check if a number n is prime."""
    if n <= 1:
        return False
    if n <= 3:
        return True
    if n % 2 == 0 or n % 3 == 0:
        return False
    
    i = 5
    while i * i <= n:
        if n % i == 0 or n % (i + 2) == 0:
            return False
        i += 6
    
    return True

# Example usage
number = 29
if is_prime(number):
    print(f"{number} is a prime number.")
else:
    print(f"{number} is not a prime number.")

# Test case
assert is_prime(29) == True, "Test case 1 failed"
assert is_prime(15) == False, "Test case 2 failed"
assert is_prime(2) == True, "Test case 3 failed"
assert is_prime(1) == False, "Test case 4 failed"

print("All test cases passed.")
```

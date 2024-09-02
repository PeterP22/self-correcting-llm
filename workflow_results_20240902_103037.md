# Self-Correcting LLM Coding Workflow Results

## Initial Query
```
Find the second largest number in a list of integers
```

## Attempts
### Attempt 1/2
#### Generated Function
```python
def find_second_largest(nums):
    if len(nums) < 2:
        raise ValueError("List must contain at least two numbers.")

    # Initialize first and second largest to negative infinity
    first = second = float('-inf')
    
    for num in nums:
        if num > first:
            second = first
            first = num
        elif first > num > second:
            second = num

    if second == float('-inf'):
        raise ValueError("List does not contain a second distinct largest number.")
    
    return second

# Example usage and test case:
nums = [4, 1, 3, 2, 5]
second_largest = find_second_largest(nums)
print(f"The second largest number is: {second_largest}")
```

#### Test Case
```python

```

#### Example Usage
```python
def find_second_largest(nums):
    if len(nums) < 2:
        raise ValueError("List must contain at least two numbers.")

    # Initialize first and second largest to negative infinity
    first = second = float('-inf')
    
    for num in nums:
        if num > first:
            second = first
            first = num
        elif first > num > second:
            second = num

    if second == float('-inf'):
        raise ValueError("List does not contain a second distinct largest number.")
    
    return second

# Example usage and test case:
nums = [4, 1, 3, 2, 5]
second_largest = find_second_largest(nums)
print(f"The second largest number is: {second_largest}")
```

## Final Results
### Success: Function passed all tests
#### Final Function
```python
def find_second_largest(nums):
    if len(nums) < 2:
        raise ValueError("List must contain at least two numbers.")

    # Initialize first and second largest to negative infinity
    first = second = float('-inf')
    
    for num in nums:
        if num > first:
            second = first
            first = num
        elif first > num > second:
            second = num

    if second == float('-inf'):
        raise ValueError("List does not contain a second distinct largest number.")
    
    return second

# Example usage and test case:
nums = [4, 1, 3, 2, 5]
second_largest = find_second_largest(nums)
print(f"The second largest number is: {second_largest}")
```

#### Example Usage
```python
def find_second_largest(nums):
    if len(nums) < 2:
        raise ValueError("List must contain at least two numbers.")

    # Initialize first and second largest to negative infinity
    first = second = float('-inf')
    
    for num in nums:
        if num > first:
            second = first
            first = num
        elif first > num > second:
            second = num

    if second == float('-inf'):
        raise ValueError("List does not contain a second distinct largest number.")
    
    return second

# Example usage and test case:
nums = [4, 1, 3, 2, 5]
second_largest = find_second_largest(nums)
print(f"The second largest number is: {second_largest}")
```

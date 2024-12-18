# Array-Based Algorithms in Java

This project provides implementations of commonly used algorithms for array problems, including:

- **Two Sum**: Finds two numbers in an array that add up to a given target.
- **Three Sum**: Finds all unique triplets in an array that sum to zero.
- **Three Sum Closest**: Finds the sum of three numbers closest to a given target.
- **Four Sum**: Finds all unique quadruplets in an array that sum to a given target.

### Example Output

```plaintext
Two Sum result: [0, 1]
Three Sum result: [[-1, -1, 2], [-1, 0, 1]]
Three Sum Closest result: 2
Four Sum result: [[-2, -1, 1, 2], [-2, 0, 0, 2], [-1, 0, 0, 1]]
```

## Algorithm Details

### Two Sum

- **Description**: Finds two indices of numbers in the array that add up to the target.
- **Method**: Utilizes a hash map for efficient lookups.
- **Complexity**: O(n) time, O(n) space.

### Three Sum

- **Description**: Finds unique triplets in the array that sum to zero.
- **Method**: Sorts the array and uses a two-pointer approach.
- **Complexity**: O(n^2) time, O(n) space.

### Three Sum Closest

- **Description**: Finds the sum of three numbers closest to a target value.
- **Method**: Similar to Three Sum but prioritizes minimizing the difference.
- **Complexity**: O(n^2) time, O(1) space.

### Four Sum

- **Description**: Finds unique quadruplets in the array that sum to a target value.
- **Method**: Extends Three Sum by adding another loop.
- **Complexity**: O(n^3) time, O(n) space.
"# LeetCode_Sum" 

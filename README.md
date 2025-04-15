Importance of Functions
1. *Modularity*: Breaks down code into smaller, manageable chunks.
2. *Reusability*: Reduces code duplication and improves efficiency.
3. *Abstraction*: Hides implementation details, focusing on interface and functionality.
4. *Readability*: Improves code readability and maintainability.

Implementing Functions
*Nth Root Function*
```
def nth_root(base, n):
    if base < 0 and n % 2 == 0:
        raise ValueError("Cannot calculate even root of negative number")
    return base ** (1 / n)
```

*Euclidean Distance Function*
```
import math

def euclidean_distance(x1, y1, x2, y2):
    return math.sqrt((x2 - x1) ** 2 + (y2 - y1) ** 2)
```

Example Usage
```
print(nth_root(27, 3))  # Output: 3.0
print(euclidean_distance(1, 2, 4, 6))  # Output: 5.0
```

Functions make code more efficient, readable, and maintainable.

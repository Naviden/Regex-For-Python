# Compiling Regex

Compiling a regex improves performance, especially for complex patterns used multiple times.

### `re.compile()`
Compiles a regex pattern into a regex object.

Example:
```python
import re
pattern = re.compile(r"\d+")
text = "There are 123 apples"
match = pattern.search(text)
print(match.group())  # Output: 123
```

Continue to [Practical Examples](./Practical_Examples.md)
# Debugging Regex

Tools and techniques for debugging regex patterns.

### Online Tools
- [Regex101](https://regex101.com/): Provides a detailed explanation of regex patterns.

### Verbose Mode
Use verbose mode for complex patterns to improve readability.

Example:
```python
import re
pattern = re.compile(r"""
    \d+  # Match one or more digits
    """, re.VERBOSE)
text = "123 456 789"
matches = pattern.findall(text)
print(matches)  # Output: ['123', '456', '789']
```
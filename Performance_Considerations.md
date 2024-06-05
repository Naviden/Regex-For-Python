# Performance Considerations

Tips to improve regex performance.

### Use Raw Strings
Always use raw strings for regex patterns to avoid escape character issues.

### Compile Regex
Compile regex patterns for repeated use.

Example:
```python
import re
pattern = re.compile(r"\d+")
text = "123 456 789"
matches = pattern.findall(text)
print(matches)  # Output: ['123', '456', '789']
```

Continue to [Debugging Regex](./Debugging_Regex.md)
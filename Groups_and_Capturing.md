# Groups and Capturing

Groups allow parts of a regex to be treated as a single unit.

### Using Parentheses for Grouping
Parentheses `()` are used to group parts of the regex.

### Capturing Groups
The content within the parentheses can be captured and reused.

Example:
```python
import re
pattern = r"(hello) (world)"
text = "hello world"
match = re.search(pattern, text)
print(match.group(1))  # Output: hello
print(match.group(2))  # Output: world
```

Continue to [Special Sequences](./Special_Sequences.md)
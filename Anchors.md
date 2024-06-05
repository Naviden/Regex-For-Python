# Anchors

Anchors are used to specify positions within a string.

### Types of Anchors
- `^`: Start of the string
- `$`: End of the string
- `\b`: Word boundary
- `\B`: Non-word boundary

Example:
```python
import re
pattern = r"^start"
text = "start of the line"
match = re.search(pattern, text)
print(match.group())  # Output: start
```


Continue to [Groups and Capturing](./Groups_and_Capturing.md)
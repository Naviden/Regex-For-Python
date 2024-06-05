# Quantifiers

Quantifiers specify how many instances of a character or group are required.

### Types of Quantifiers
- `*`: 0 or more
- `+`: 1 or more
- `?`: 0 or 1
- `{n}`: Exactly n times
- `{n,}`: At least n times
- `{n,m}`: Between n and m times

Example:
```python
import re
pattern = r"a{2,3}"
text = "aaa aa aaaa"
matches = re.findall(pattern, text)
print(matches)  # Output: ['aaa', 'aa', 'aaa']
```

Continue to [Anchors](./Anchors.md)
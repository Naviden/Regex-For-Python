# Character Classes

Character classes match any one of a set of characters. 

### Predefined Character Classes
- `\d`: Matches any digit (equivalent to `[0-9]`).
- `\D`: Matches any non-digit.
- `\w`: Matches any word character (alphanumeric plus underscore).
- `\W`: Matches any non-word character.
- `\s`: Matches any whitespace character.
- `\S`: Matches any non-whitespace character.

Example:
```python
import re
pattern = r"\d+"
text = "There are 123 apples"
matches = re.findall(pattern, text)
print(matches)  # Output: ['123']
```

Continue to [Quantifiers](./Quantifiers.md)
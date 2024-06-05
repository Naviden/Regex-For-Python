# Lookahead and Lookbehind

Lookahead and lookbehind are used to match patterns based on what follows or precedes them, without including those characters in the match.

### Lookahead
- `(?=...)`: Positive lookahead
- `(?!...)`: Negative lookahead

### Lookbehind
- `(?<=...)`: Positive lookbehind
- `(?<!...)`: Negative lookbehind

Example:
```python
import re
pattern = r"\bword(?=\.)"
text = "This is a word."
match = re.search(pattern, text)
print(match.group())  # Output: word
```
Continue to [Using Regex in Python](./Using_Regex_in_Python.md)
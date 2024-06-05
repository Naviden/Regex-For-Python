# Special Sequences

Special sequences simplify the writing of complex regex patterns.

### Common Special Sequences
- `\A`: Matches the start of the string.
- `\Z`: Matches the end of the string.
- `\b`: Matches a word boundary.
- `\B`: Matches a non-word boundary.

Example:
```python
import re
pattern = r"\bword\b"
text = "a word in a sentence"
match = re.search(pattern, text)
print(match.group())  # Output: word
```

Continue to [Lookahead and Lookbehind](./Lookahead_and_Lookbehind.md)
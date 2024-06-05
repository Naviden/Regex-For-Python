# Basic Characters

### Literal Characters
Most characters, including letters and numbers, match themselves.

Example:
```python
import re
pattern = r"hello"
text = "hello world"
match = re.search(pattern, text)
print(match.group())  # Output: hello
```
Metacharacters

Some characters have special meanings in regex:

- `.`: Matches any character except a newline.
- `^`: Matches the start of the string.
- `$`: Matches the end of the string.
- `*`: Matches 0 or more repetitions of the preceding element.
- `+`: Matches 1 or more repetitions of the preceding element.
- `?`: Matches 0 or 1 repetition of the preceding element.
- `[]`: Matches any one of the characters inside the brackets.
- `|`: Acts as a logical OR.

Continue to [Character Classes](./Character_Classes.md)
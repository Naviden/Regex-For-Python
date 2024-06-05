# Basic Functions

### `re.search()`
Searches for a match of the regex pattern in the string.

Example:
```python
import re
pattern = r"hello"
text = "hello world"
match = re.search(pattern, text)
print(match.group())  # Output: hello
```

### `re.match()`

Matches the regex pattern at the beginning of the string.

Example:

```python
import re
pattern = r"hello"
text = "hello world"
match = re.match(pattern, text)
print(match.group())  # Output: hello
```


### `re.findall()`

Finds all matches of the regex pattern in the string.

Example:
```python
import re
pattern = r"\d+"
text = "There are 123 apples and 456 oranges"
matches = re.findall(pattern, text)
print(matches)  # Output: ['123', '456']
```




### `re.sub()`

Replaces matches of the regex pattern with a string.

Example:
```python
import re
pattern = r"apples"
text = "I have apples"
replaced_text = re.sub(pattern, "oranges", text)
print(replaced_text)  # Output: I have oranges
```

Continue to [Compiling Regex](./Compiling_Regex.md)
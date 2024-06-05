# Text Extraction

Use regex to extract specific pieces of data from text.

### Extracting Numbers
Example:
```python
import re
pattern = r"\d+"
text = "Order number 12345"
match = re.search(pattern, text)
print(match.group())  # Output: 12345
```
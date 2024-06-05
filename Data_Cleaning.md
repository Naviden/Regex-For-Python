# Data Cleaning

Use regex to clean and preprocess textual data.

### Removing Special Characters
Example:
```python
import re
pattern = r"[^\w\s]"
text = "Hello, world!"
cleaned_text = re.sub(pattern, "", text)
print(cleaned_text)  # Output: Hello world
```

Continue to [Advanced Topics](./Advanced_Topics.md)
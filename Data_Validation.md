# Data Validation

Use regex to validate data formats such as emails, phone numbers, and more.

### Email Validation
Example:
```python
import re
pattern = r"^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$"
text = "test@example.com"
match = re.match(pattern, text)
print(bool(match))  # Output: True
```

Continue to [Text Extraction](./Text_Extraction.md)
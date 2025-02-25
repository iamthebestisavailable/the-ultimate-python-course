Here's a well-formatted Markdown guide on **String Slicing in Python**:

```md
# String Slicing in Python

String slicing allows extracting a portion of a string using the syntax:

```python
string[start:stop:step]
```

## 1. Basic Slicing

- `start`: The starting index (inclusive).
- `stop`: The ending index (exclusive).
- `step`: The step (default is `1`).

### Example:
```python
text = "Hello, World!"
print(text[0:5])  # Output: Hello
print(text[:5])   # Output: Hello (start defaults to 0)
print(text[7:])   # Output: World! (goes till end)
print(text[:])    # Output: Hello, World! (entire string)
```

## 2. Using Negative Indices
Python allows negative indexing from the end of the string.

### Example:
```python
text = "Hello, World!"
print(text[-6:])   # Output: World!
print(text[-6:-1]) # Output: World
```

## 3. Using Steps in Slicing

### Example:
```python
text = "Hello, World!"
print(text[::2])   # Output: Hlo ol!
print(text[::-1])  # Output: !dlroW ,olleH (reverses string)
```

## 4. Common Use Cases

- **Reverse a string**: `text[::-1]`
- **Extract first n characters**: `text[:n]`
- **Extract last n characters**: `text[-n:]`
- **Skip characters**: `text[::2]` (every second character)

## 5. Edge Cases

- If `start >= stop`, the result is an empty string:
  ```python
  print("Python"[5:2])  # Output: ''
  ```
- If `step` is `0`, it raises a `ValueError`.

## Conclusion

String slicing is a powerful feature that allows flexible string manipulation in Python.

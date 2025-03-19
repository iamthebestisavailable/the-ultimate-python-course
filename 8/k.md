### For Loop
A `for` loop is used to iterate over a sequence (such as a list, tuple, dictionary, set, or string) and execute a block of code for each item in the sequence.

Here's a basic example of a `for` loop that prints each item in a list:

```python
fruits = ['apple', 'banana', 'cherry']
for fruit in fruits:
    print(fruit)
```

This will output:
```
apple
banana
cherry
```

### While Loop
A `while` loop is used to execute a block of code as long as a specified condition is true.

Here's a basic example of a `while` loop that prints numbers from 1 to 5:

```python
i = 1
while i <= 5:
    print(i)
    i += 1
```

This will output:
```
1
2
3
4
5
```

### Loop Control Statements
Python also provides several control statements to control the flow of loops:

1. **`break`**: Terminates the loop and proceeds to the next statement after the loop.
2. **`continue`**: Skips the remaining code inside the loop for the current iteration and moves to the next iteration.
3. **`pass`**: Does nothing and acts as a placeholder for future code.

Here's an example using `break` and `continue`:

```python
for num in range(1, 10):
    if num == 5:
        break  # Terminates the loop when num is 5
    if num % 2 == 0:
        continue  # Skips the even numbers
    print(num)
```

This will output:
```
1
3
```
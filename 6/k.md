### **Operators in Python**  
Operators in Python are special symbols that perform operations on variables and values. Python provides several types of operators:

---

## **1. Arithmetic Operators**  
Used for mathematical calculations.  

| Operator | Description       | Example (`a = 10, b = 3`) |
|----------|------------------|--------------------------|
| `+`      | Addition         | `a + b  # 10 + 3 = 13`  |
| `-`      | Subtraction      | `a - b  # 10 - 3 = 7`   |
| `*`      | Multiplication   | `a * b  # 10 * 3 = 30`  |
| `/`      | Division         | `a / b  # 10 / 3 = 3.33` |
| `%`      | Modulus (Remainder) | `a % b  # 10 % 3 = 1` |
| `**`     | Exponentiation   | `a ** b # 10^3 = 1000` |

---

## **2. Comparison (Relational) Operators**  
Used to compare two values, returning `True` or `False`.  

| Operator | Description       | Example (`a = 10, b = 3`) |
|----------|------------------|--------------------------|
| `==`     | Equal to         | `a == b  # False` |
| `!=`     | Not equal to     | `a != b  # True`  |
| `>`      | Greater than     | `a > b   # True`  |
| `<`      | Less than        | `a < b   # False` |
| `>=`     | Greater or equal | `a >= b  # True`  |
| `<=`     | Less or equal    | `a <= b  # False` |

---

## **3. Logical Operators**  
Used to combine conditional statements.

| Operator | Description | Example (`x = True, y = False`) |
|----------|------------|-------------------------------|
| `and`   | Returns `True` if both conditions are `True` | `x and y  # False` |
| `or`    | Returns `True` if at least one condition is `True` | `x or y  # True` |
| `not`   | Reverses the logical state | `not x  # False` |

---

## **4. Bitwise Operators**  
Work on bits (binary representation of numbers).  

| Operator | Description | Example (`a = 5 (0101), b = 3 (0011)`) |
|----------|------------|----------------------------------------|
| `&` (AND) | Sets bits to 1 if both bits are 1 | `a & b  # 0101 & 0011 = 0001 (1)` |
| `|` (OR) | Sets bits to 1 if at least one bit is 1 | `a | b  # 0101 | 0011 = 0111 (7)` |
| `^` (XOR) | Sets bits to 1 if only one bit is 1 | `a ^ b  # 0101 ^ 0011 = 0110 (6)` |
| `~` (NOT) | Inverts all bits | `~a  # -6` (2’s complement) |
| `<<` (Left Shift) | Shifts bits left (multiplies by 2) | `a << 1  # 1010 (10)` |
| `>>` (Right Shift) | Shifts bits right (divides by 2) | `a >> 1  # 0010 (2)` |

---

## **5. Assignment Operators**  
Used to assign values to variables.

| Operator | Description | Example (`x = 5`) |
|----------|------------|-------------------|
| `=`      | Assigns value | `x = 5` |
| `+=`     | Adds and assigns | `x += 2  # x = x + 2` |
| `-=`     | Subtracts and assigns | `x -= 2  # x = x - 2` |
| `*=`     | Multiplies and assigns | `x *= 2  # x = x * 2` |
| `/=`     | Divides and assigns | `x /= 2  # x = x / 2` |
| `%=`     | Modulus and assigns | `x %= 2  # x = x % 2` |
| `**=`    | Exponentiation and assigns | `x **= 2  # x = x ** 2` |

---

## **6. Identity Operators**  
Used to compare memory locations of objects.

| Operator | Description | Example |
|----------|------------|---------|
| `is`     | Returns `True` if both objects are the same | `x is y` |
| `is not` | Returns `True` if objects are different | `x is not y` |

---

## **7. Membership Operators**  
Used to check if a value exists in a sequence.

| Operator | Description | Example (`list1 = [1, 2, 3]`) |
|----------|------------|-----------------------------|
| `in`     | Returns `True` if value is in sequence | `2 in list1  # True` |
| `not in` | Returns `True` if value is not in sequence | `5 not in list1  # True` |

---

### **Example Code**
```python
a, b = 10, 3

# Arithmetic Operators
print(a + b)  # 13
print(a - b)  # 7
print(a * b)  # 30
print(a / b)  # 3.33
print(a // b) # 3
print(a % b)  # 1
print(a ** b) # 1000

# Comparison Operators
print(a > b)  # True
print(a == b) # False

# Logical Operators
x, y = True, False
print(x and y) # False
print(x or y)  # True

# Identity Operators
list1 = [1, 2, 3]
list2 = list1
print(list1 is list2)  # True

# Membership Operators
print(2 in list1)  # True
print(5 not in list1)  # True
```
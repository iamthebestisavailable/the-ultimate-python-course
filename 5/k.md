### Conditional Statements in Python

#### 1. Basic if Statement
- **Syntax**:
  ```python
  if condition:
      # block of code to execute if condition is true
  ```
- **Example**:
  ```python
  age = 18
  if age >= 18:
      print("You are eligible to vote.")
  ```

#### 2. else Statement
- **Syntax**:
  ```python
  if condition:
      # block of code if condition is true
  else:
      # block of code if condition is false
  ```
- **Example**:
  ```python
  age = 16
  if age >= 18:
      print("You are eligible to vote.")
  else:
      print("You are not eligible to vote.")
  ```

#### 3. elif Statement
- **Syntax**:
  ```python
  if condition1:
      # block of code if condition1 is true
  elif condition2:
      # block of code if condition2 is true
  else:
      # block of code if both conditions are false
  ```
- **Example**:
  ```python
  marks = 75
  if marks >= 90:
      print("Grade: A")
  elif marks >= 75:
      print("Grade: B")
  elif marks >= 60:
      print("Grade: C")
  else:
      print("Grade: D")
  ```

#### 4. Nested Conditional Statements
- **Example**:
  ```python
  num = 10
  if num > 0:
      print("Positive number")
      if num % 2 == 0:
          print("Even number")
  else:
      print("Negative number or zero")
  ```

#### 5. Logical Operators
- **and**: True if both conditions are true.
- **or**: True if at least one condition is true.
- **not**: Reverses the truth value.

- **Example**:
  ```python
  age = 20
  citizen = True

  if age >= 18 and citizen:
      print("You can vote.")
  else:
      print("You cannot vote.")
  ```

#### 6. Ternary Conditional Operator
- **Syntax**:
  ```python
  value = "Eligible" if age >= 18 else "Not Eligible"
  print(value)
  ```

#### 7. Conclusion
- Conditional statements are fundamental in programming, allowing you to control the flow of execution based on conditions. They help in making decisions in the code, enabling dynamic and responsive applications. Understanding and using these statements effectively is crucial for developing robust Python programs.

Is there anything specific you would like to dive deeper into or any examples you need more elaboration on?
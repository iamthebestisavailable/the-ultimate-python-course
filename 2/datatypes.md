In Python, data types define the type of a variable. Here are the main built-in data types:

### **1. Numeric Types**
- **`int`** – Integer values (e.g., `10`, `-5`)
- **`float`** – Floating-point numbers (e.g., `10.5`, `-3.14`)
- **`complex`** – Complex numbers (e.g., `3+5j`, `-2j`)

### **2. Sequence Types**
- **`str`** – String (e.g., `"hello"`, `'Python'`)
- **`list`** – Ordered, mutable collection (e.g., `[1, 2, 3]`)
- **`tuple`** – Ordered, immutable collection (e.g., `(1, 2, 3)`)
- **`range`** – Sequence of numbers (e.g., `range(5)` → `[0, 1, 2, 3, 4]`)

### **3. Set Types**
- **`set`** – Unordered, unique collection (e.g., `{1, 2, 3}`)
- **`frozenset`** – Immutable set (e.g., `frozenset({1, 2, 3})`)

### **4. Mapping Type**
- **`dict`** – Key-value pairs (e.g., `{"name": "Alice", "age": 25}`)

### **5. Boolean Type**
- **`bool`** – Boolean values (`True`, `False`)

### **7. None Type**
- **`NoneType`** – Represents the absence of a value (`None`)

Each type can be checked using `type(variable)`, and Python supports dynamic typing, meaning variables do not need an explicit type declaration.

Here’s an improved version of your table with better organization, alignment, and clarity:  

| **Data Type**   | **Category**       | **Description**                          | **Example**                 |
|---------------|----------------|----------------------------------|----------------------------|
| **Numeric Types** | | | |
| `int`         | Integer         | Whole numbers                   | `10`, `-5`, `1000`         |
| `float`       | Floating Point  | Decimal numbers                 | `3.14`, `-0.01`            |
| `complex`     | Complex Number  | Numbers with real & imaginary parts | `3 + 4j`                  |
| **Sequence Types** | | | |
| `str`         | String          | Sequence of characters          | `"Hello"`, `'Python'`      |
| `list`        | List            | Ordered, mutable collection     | `[1, 2, "Python"]`        |
| `tuple`       | Tuple           | Ordered, immutable collection   | `(1, 2, "Python")`        |
| `range`       | Range           | Sequence of numbers             | `range(5) → [0,1,2,3,4]`  |
| **Set Types** | | | |
| `set`         | Set             | Unordered, unique elements      | `{1, 2, 3}`               |
| `frozenset`   | Frozen Set      | Immutable set                   | `frozenset({1, 2, 3})`    |
| **Mapping Type** | | | |
| `dict`        | Dictionary      | Key-value pairs                 | `{"name": "John", "age": 30}` |
| **Boolean Type** | | | |
| `bool`        | Boolean         | `True` or `False` values        | `True`, `False`            |
| **Binary Types** | | | |
| `bytes`       | Bytes           | Immutable sequence of bytes     | `b"hello"`                |
| `bytearray`   | Byte Array      | Mutable sequence of bytes       | `bytearray(b"hello")`     |
| `memoryview`  | Memory View     | View of byte-oriented data      | `memoryview(b"hello")`    |

<!-- Now it's more readable and structured! Do you need any more refinements? 😊 -->
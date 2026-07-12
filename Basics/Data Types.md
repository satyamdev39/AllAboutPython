# 🗂️ Python Data Types

Data types define the **type of data** stored inside a variable. Python automatically identifies the data type when a value is assigned.

Example:

```python
name = "Python"
age = 30
```

Here:
- `name` → String (`str`)
- `age` → Integer (`int`)

---

# 🐍 Built-in Data Types in Python

Python has several built-in data types:

| Category | Data Types |
|----------|------------|
| 🔢 Numeric | `int`, `float`, `complex` |
| 🔤 Text | `str` |
| 📋 Sequence | `list`, `tuple`, `range` |
| 🎯 Set | `set`, `frozenset` |
| 📚 Mapping | `dict` |
| ✅ Boolean | `bool` |
| 💾 Binary | `bytes`, `bytearray`, `memoryview` |

---

# 🔢 1. Numeric Data Types

## 🔹 Integer (`int`)

Stores whole numbers without decimal values.

Example:

```python
age = 25

print(age)
print(type(age))
```

### 📤 Output

```text
25
<class 'int'>
```

---

## 🔹 Float (`float`)

Stores decimal numbers.

Example:

```python
price = 99.99

print(price)
print(type(price))
```

### 📤 Output

```text
99.99
<class 'float'>
```

---

## 🔹 Complex (`complex`)

Stores complex numbers with real and imaginary parts.

Example:

```python
number = 2 + 3j

print(number)
print(type(number))
```

### 📤 Output

```text
(2+3j)
<class 'complex'>
```

---

# 🔤 2. String (`str`)

Strings store text values. They are written inside quotes.

Example:

```python
name = "Python"

print(name)
print(type(name))
```

### 📤 Output

```text
Python
<class 'str'>
```

Properties:
- Ordered
- Immutable
- Supports indexing and slicing

Example:

```python
language = "Python"

print(language[0])
```

Output:

```text
P
```

---

# 📋 3. List (`list`)

A list stores multiple values in a single variable.

Properties:
- Ordered
- Mutable (can be changed)
- Allows duplicate values

Example:

```python
numbers = [10, 20, 30]

numbers.append(40)

print(numbers)
```

### 📤 Output

```text
[10, 20, 30, 40]
```

---

# 📦 4. Tuple (`tuple`)

A tuple is similar to a list but it cannot be modified.

Properties:
- Ordered
- Immutable
- Allows duplicate values

Example:

```python
colors = ("red", "blue", "green")

print(colors)
```

### 📤 Output

```text
('red', 'blue', 'green')
```

---

# 🎯 5. Set (`set`)

A set stores unique values.

Properties:
- Unordered
- Mutable
- Does not allow duplicates

Example:

```python
numbers = {1, 2, 2, 3}

print(numbers)
```

### 📤 Output

```text
{1, 2, 3}
```

---

# 📚 6. Dictionary (`dict`)

A dictionary stores data in **key-value pairs**.

Example:

```python
student = {
    "name": "John",
    "age": 20
}

print(student)
```

### 📤 Output

```text
{'name': 'John', 'age': 20}
```

Properties:
- Ordered
- Mutable
- Keys must be unique

---

# ✅ 7. Boolean (`bool`)

Boolean stores only two values:

- `True`
- `False`

Example:

```python
is_python_easy = True

print(is_python_easy)
```

### 📤 Output

```text
True
```

---

# 🔍 Checking Data Type

Use the `type()` function:

```python
x = 100

print(type(x))
```

### 📤 Output

```text
<class 'int'>
```

---

# 🔄 Type Conversion (Type Casting)

Converting one data type into another is called type casting.

Example:

```python
number = "100"

new_number = int(number)

print(new_number)
print(type(new_number))
```

### 📤 Output

```text
100
<class 'int'>
```

---

# ⚖️ Mutable vs Immutable Data Types

## 🔄 Mutable (Can be changed)

Examples:

- 📋 List
- 📚 Dictionary
- 🎯 Set

Example:

```python
numbers = [1, 2, 3]

numbers.append(4)

print(numbers)
```

---

## 🔒 Immutable (Cannot be changed)

Examples:

- 🔤 String
- 📦 Tuple
- 🔢 Integer
- 💯 Float

Example:

```python
name = "Python"

name = name + " Programming"

print(name)
```

---

# 🎯 Interview Questions

## 1. What are data types in Python?

**Answer:**

Data types define the type of value stored in a variable. They tell Python how to handle that data.

---

## 2. What are the main data types in Python?

**Answer:**

- int
- float
- complex
- str
- list
- tuple
- set
- dictionary
- bool

---

## 3. Difference between List and Tuple?

| List 📋 | Tuple 📦 |
|---|---|
| Mutable | Immutable |
| Uses `[]` | Uses `()` |
| Slower | Faster |

---

## 4. Difference between Set and List?

**Answer:**

- List allows duplicates and maintains order.
- Set stores unique values and is unordered.

---

## 5. How do you check the data type of a variable?

**Answer:**

Using the `type()` function.

Example:

```python
type(variable)
```

---

## 6. What are mutable objects?

**Answer:**

Objects whose values can be changed after creation are called mutable objects.

Examples:
- List
- Dictionary
- Set

---

## 7. What are immutable objects?

**Answer:**

Objects whose values cannot be changed after creation are called immutable objects.

Examples:
- String
- Tuple
- Integer

---

# 🚀 Summary

Python provides different data types to store different kinds of information.

Understanding data types helps in:
- Writing efficient programs
- Managing memory
- Choosing the right data structure

🐍 Keep learning Python!

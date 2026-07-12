# ⚙️ Python Operators

Operators are special symbols or keywords used to perform operations on variables and values.

Example:

```python
a = 10
b = 5

print(a + b)
```

### 📤 Output

```text
15
```

---

# 🔢 Types of Python Operators

Python provides different types of operators:

1. ➕ Arithmetic Operators
2. 🔍 Comparison Operators
3. 🔄 Assignment Operators
4. 🔗 Logical Operators
5. 📦 Membership Operators
6. 🧠 Identity Operators
7. ⚡ Bitwise Operators

---

# ➕ 1. Arithmetic Operators

Used to perform mathematical operations.

| Operator | Description | Example |
|----------|-------------|---------|
| `+` | Addition | `10 + 5 = 15` |
| `-` | Subtraction | `10 - 5 = 5` |
| `*` | Multiplication | `10 * 5 = 50` |
| `/` | Division | `10 / 5 = 2` |
| `%` | Modulus (remainder) | `10 % 3 = 1` |
| `//` | Floor Division | `10 // 3 = 3` |
| `**` | Power | `2 ** 3 = 8` |

Example:

```python
a = 10
b = 3

print(a + b)
print(a % b)
print(a ** b)
```

### 📤 Output

```text
13
1
1000
```

---

# 🔍 2. Comparison Operators

Used to compare two values. It returns `True` or `False`.

| Operator | Description |
|----------|-------------|
| `==` | Equal to |
| `!=` | Not equal to |
| `>` | Greater than |
| `<` | Less than |
| `>=` | Greater than or equal |
| `<=` | Less than or equal |

Example:

```python
a = 10
b = 5

print(a > b)
print(a == b)
```

### 📤 Output

```text
True
False
```

---

# 🔄 3. Assignment Operators

Used to assign values to variables.

| Operator | Example |
|----------|---------|
| `=` | `x = 10` |
| `+=` | `x += 5` |
| `-=` | `x -= 5` |
| `*=` | `x *= 5` |
| `/=` | `x /= 5` |

Example:

```python
x = 10

x += 5

print(x)
```

### 📤 Output

```text
15
```

---

# 🔗 4. Logical Operators

Used to combine multiple conditions.

| Operator | Description |
|----------|-------------|
| `and` | Returns True if both conditions are true |
| `or` | Returns True if any condition is true |
| `not` | Reverses the result |

Example:

```python
age = 20

print(age > 18 and age < 30)
```

### 📤 Output

```text
True
```

---

# 📦 5. Membership Operators

Used to check whether a value exists in a sequence.

Operators:

- `in`
- `not in`

Example:

```python
name = "Python"

print("P" in name)
print("z" not in name)
```

### 📤 Output

```text
True
True
```

---

# 🧠 6. Identity Operators

Used to compare whether two variables refer to the same object in memory.

Operators:

- `is`
- `is not`

Example:

```python
a = [1, 2]
b = a

print(a is b)
```

### 📤 Output

```text
True
```

---

# ⚡ 7. Bitwise Operators

Used to perform operations on binary numbers.

| Operator | Description |
|----------|-------------|
| `&` | AND |
| `|` | OR |
| `^` | XOR |
| `~` | NOT |
| `<<` | Left Shift |
| `>>` | Right Shift |

Example:

```python
a = 5
b = 3

print(a & b)
```

### 📤 Output

```text
1
```

---

# 🎯 Interview Questions

## 1. What are operators in Python?

**Answer:**

Operators are symbols or keywords used to perform operations on values and variables.

---

## 2. What is the difference between `==` and `is`?

**Answer:**

- `==` compares values.
- `is` compares memory locations.

---

## 3. What is the difference between `/` and `//`?

**Answer:**

- `/` returns normal division result.
- `//` returns floor division result.

Example:

```python
print(10 / 3)
print(10 // 3)
```

Output:

```text
3.3333333333333335
3
```

---

## 4. What are logical operators?

**Answer:**

Logical operators are used to combine conditions:

- `and`
- `or`
- `not`

---

## 5. What is the difference between `in` and `is`?

**Answer:**

- `in` checks membership.
- `is` checks object identity.

---

# 🚀 Summary

Python operators help developers perform:

✅ Mathematical calculations  
✅ Value comparisons  
✅ Logical decisions  
✅ Object comparisons  
✅ Data checking  

Understanding operators is essential for writing efficient Python programs. 🐍

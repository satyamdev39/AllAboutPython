# 🔤 Python Strings

A **string** is a sequence of characters enclosed inside single quotes (`' '`), double quotes (`" "`), or triple quotes (`''' '''`).

Example:

```python
name = "Python"

print(name)
```

### 📤 Output

```text
Python
```

---

# ✨ Features of Strings

- 🔤 Collection of characters
- 🔢 Supports indexing
- ✂️ Supports slicing
- 🔒 Immutable (cannot be changed)
- 🔄 Supports many built-in methods
- 📚 Can store text data

---

# 📝 Creating Strings

## Single Quotes

```python
name = 'Python'
```

## Double Quotes

```python
name = "Python"
```

## Triple Quotes

Used for multi-line strings.

```python
message = """
Hello
Welcome to Python
"""
```

---

# 🔢 String Indexing

Each character has an index position.

Example:

```python
text = "Python"

print(text[0])
print(text[5])
```

### 📤 Output

```text
P
n
```

### Negative Indexing

Python allows negative indexing:

```python
text = "Python"

print(text[-1])
print(text[-2])
```

Output:

```text
n
o
```

---

# ✂️ String Slicing

Slicing is used to extract parts of a string.

Syntax:

```python
string[start:end:step]
```

Example:

```python
text = "Python"

print(text[0:3])
print(text[2:])
print(text[::-1])
```

### 📤 Output

```text
Pyt
thon
nohtyP
```

---

# ➕ String Concatenation

Joining two or more strings is called concatenation.

Example:

```python
first = "Hello"
second = "Python"

result = first + " " + second

print(result)
```

Output:

```text
Hello Python
```

---

# 🔁 String Repetition

Using `*` repeats a string.

Example:

```python
text = "Hi "

print(text * 3)
```

Output:

```text
Hi Hi Hi
```

---

# 🔍 Checking String Length

Use the `len()` function.

Example:

```python
text = "Python"

print(len(text))
```

Output:

```text
6
```

---

# 🔎 Membership Operators

Used to check whether a value exists in a string.

Operators:

- `in`
- `not in`

Example:

```python
text = "Python"

print("Py" in text)
print("Java" not in text)
```

Output:

```text
True
True
```

---

# 🔒 String Immutability

Strings cannot be modified after creation.

Example:

```python
name = "Python"

# name[0] = "J" ❌ Error
```

Instead, create a new string:

```python
name = "Python"

name = "J" + name[1:]

print(name)
```

Output:

```text
Jython
```

---

# 🎯 Interview Quick Points

- String is an immutable data type.
- Strings support indexing and slicing.
- Strings can be created using single, double, or triple quotes.
- String methods return new strings instead of modifying the original.

---

# 🚀 Summary

Python strings are used to store and manipulate text data.

Important concepts:

✅ Creating strings  
✅ Indexing  
✅ Slicing  
✅ Concatenation  
✅ String methods  
✅ String formatting  

🐍 Keep learning Python!

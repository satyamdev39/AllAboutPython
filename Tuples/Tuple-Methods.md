# 📦 Python Tuple Methods

Tuples are immutable, so they have fewer methods compared to lists.

Python provides only **two built-in tuple methods**:

1. 🔍 `count()`
2. 📍 `index()`

---

# 🔢 1. count()

The `count()` method returns the number of times a specified value appears in a tuple.

### Syntax:

```python
tuple.count(value)
```

### Example:

```python
numbers = (1, 2, 3, 2, 2, 4)

print(numbers.count(2))
```

### 📤 Output:

```text
3
```

Explanation:

The value `2` appears three times in the tuple.

---

# 📍 2. index()

The `index()` method returns the index position of the first occurrence of a specified value.

### Syntax:

```python
tuple.index(value)
```

### Example:

```python
languages = ("Python", "Java", "C++")

print(languages.index("Java"))
```

### 📤 Output:

```text
1
```

Explanation:

`Java` is present at index position `1`.

---

# 🔎 Using index() with Duplicate Values

The `index()` method returns the first matching position.

Example:

```python
numbers = (10, 20, 30, 20, 40)

print(numbers.index(20))
```

### 📤 Output:

```text
1
```

---

# ⚠️ Handling ValueError

If the value does not exist, `index()` gives an error.

Example:

```python
numbers = (1, 2, 3)

print(numbers.index(5))
```

Output:

```text
ValueError
```

---

# 📋 Tuple Built-in Functions

Apart from methods, Python provides some useful built-in functions for tuples.

---

# 📏 1. len()

Returns the number of elements in a tuple.

Example:

```python
numbers = (10, 20, 30)

print(len(numbers))
```

Output:

```text
3
```

---

# 🔢 2. max()

Returns the largest value from a tuple.

Example:

```python
numbers = (10, 50, 20)

print(max(numbers))
```

Output:

```text
50
```

---

# 🔻 3. min()

Returns the smallest value from a tuple.

Example:

```python
numbers = (10, 50, 20)

print(min(numbers))
```

Output:

```text
10
```

---

# ➕ 4. sum()

Returns the sum of numeric elements.

Example:

```python
numbers = (10, 20, 30)

print(sum(numbers))
```

Output:

```text
60
```

---

# 🔄 Tuple Operations

## ➕ Concatenation

Joining two tuples using `+`.

Example:

```python
tuple1 = (1, 2)
tuple2 = (3, 4)

print(tuple1 + tuple2)
```

Output:

```text
(1, 2, 3, 4)
```

---

## ✖️ Repetition

Repeating tuple elements using `*`.

Example:

```python
numbers = (1, 2)

print(numbers * 3)
```

Output:

```text
(1, 2, 1, 2, 1, 2)
```

---

## 🔍 Membership Checking

Using:

- `in`
- `not in`

Example:

```python
fruits = ("apple", "banana")

print("apple" in fruits)
print("mango" not in fruits)
```

Output:

```text
True
True
```

---

# 📦 Tuple Packing

Creating a tuple by assigning multiple values.

Example:

```python
student = "John", 20, "Python"

print(student)
```

Output:

```text
('John', 20, 'Python')
```

---

# 📤 Tuple Unpacking

Extracting tuple values into variables.

Example:

```python
student = ("John", 20, "Python")

name, age, course = student

print(name)
print(age)
print(course)
```

Output:

```text
John
20
Python
```

---

# 📊 Tuple Methods Summary

| Method/Function | Description |
|---|---|
| `count()` | Counts occurrences of a value |
| `index()` | Finds first index of a value |
| `len()` | Returns tuple length |
| `max()` | Returns maximum value |
| `min()` | Returns minimum value |
| `sum()` | Returns total sum |

---

# 🎯 Interview Quick Questions

## 1. How many methods are available for tuples?

✅ Answer:

Python tuples have only two built-in methods:

- `count()`
- `index()`

---

## 2. Why do tuples have fewer methods than lists?

✅ Answer:

Because tuples are immutable and cannot be modified after creation.

---

## 3. Can we add or remove elements from a tuple?

✅ Answer:

No. Tuples cannot be modified directly.

---

## 4. How can you modify a tuple?

✅ Answer:

Convert it into a list, modify it, and convert it back into a tuple.

---

# 🚀 Summary

Tuple methods are limited because tuples are immutable.

Important concepts:

✅ count()  
✅ index()  
✅ Tuple operations  
✅ Packing and unpacking  
✅ Built-in functions  

📦 Tuples are useful when data should remain unchanged in a Python program.

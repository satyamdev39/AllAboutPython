# 📦 Python Tuples

A **tuple** is a built-in Python data structure used to store multiple values in a single variable.

Tuples are similar to lists, but the main difference is that **tuples are immutable**, meaning their values cannot be changed after creation.

Example:

```python
numbers = (10, 20, 30)

print(numbers)
```

### 📤 Output

```text
(10, 20, 30)
```

---

# ✨ Features of Tuples

- 📦 Ordered collection
- 🔒 Immutable (cannot be changed)
- 🔁 Allows duplicate values
- 📚 Can store different data types
- ⚡ Faster than lists
- 🧠 Uses less memory compared to lists

---

# 📝 Creating a Tuple

## Empty Tuple

```python
empty = ()

print(empty)
```

Output:

```text
()
```

---

## Tuple with Values

```python
fruits = ("apple", "banana", "mango")

print(fruits)
```

Output:

```text
('apple', 'banana', 'mango')
```

---

## Tuple with Different Data Types

```python
data = ("Python", 100, 5.5, True)

print(data)
```

Output:

```text
('Python', 100, 5.5, True)
```

---

# ⚠️ Single Element Tuple

A tuple with one element requires a comma.

❌ Incorrect:

```python
number = (10)
```

This is treated as an integer.

✅ Correct:

```python
number = (10,)

print(type(number))
```

Output:

```text
<class 'tuple'>
```

---

# 🔢 Tuple Indexing

Tuples use indexing to access elements.

Example:

```python
languages = ("Python", "Java", "C++")

print(languages[0])
```

Output:

```text
Python
```

---

# 🔙 Negative Indexing

Negative indexing starts from the end.

Example:

```python
languages = ("Python", "Java", "C++")

print(languages[-1])
```

Output:

```text
C++
```

---

# ✂️ Tuple Slicing

Slicing extracts a part of a tuple.

Syntax:

```python
tuple[start:end:step]
```

Example:

```python
numbers = (1, 2, 3, 4, 5)

print(numbers[1:4])
```

Output:

```text
(2, 3, 4)
```

---

# 🔒 Tuple Immutability

Tuples cannot be modified after creation.

Example:

```python
numbers = (1, 2, 3)

numbers[0] = 10
```

Output:

```text
TypeError
```

To modify data, convert tuple into a list.

Example:

```python
numbers = (1, 2, 3)

temp = list(numbers)

temp[0] = 10

numbers = tuple(temp)

print(numbers)
```

Output:

```text
(10, 2, 3)
```

---

# ➕ Joining Tuples

Two tuples can be joined using `+`.

Example:

```python
tuple1 = (1, 2)
tuple2 = (3, 4)

result = tuple1 + tuple2

print(result)
```

Output:

```text
(1, 2, 3, 4)
```

---

# 🔁 Repeating Tuples

Using `*` repeats tuple elements.

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

# 🔍 Checking Elements

Using `in` operator:

```python
fruits = ("apple", "banana")

print("apple" in fruits)
```

Output:

```text
True
```

---

# 📏 Tuple Length

Using `len()`:

```python
numbers = (10, 20, 30)

print(len(numbers))
```

Output:

```text
3
```

---

# 🔄 Looping Through Tuples

Example:

```python
fruits = ("apple", "banana", "mango")

for fruit in fruits:
    print(fruit)
```

Output:

```text
apple
banana
mango
```

---

# 📋 Tuple vs List

| Tuple 📦 | List 📋 |
|---|---|
| Immutable | Mutable |
| Uses `()` | Uses `[]` |
| Faster | Slower |
| Less memory | More memory |
| Cannot modify values | Can modify values |

---

# 🎯 Important Tuple Concepts

- Creating tuples
- Tuple indexing
- Tuple slicing
- Tuple packing
- Tuple unpacking
- Immutable nature
- Tuple methods

---

# 🚀 Summary

Tuples are useful when we need a collection of values that should not be changed.

Important points:

✅ Ordered  
✅ Immutable  
✅ Faster than lists  
✅ Supports indexing and slicing  
✅ Allows duplicate values  

Tuples are commonly used for storing fixed data in Python programs. 📦🐍

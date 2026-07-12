# 📋 Python Lists

A **list** is a built-in Python data structure used to store multiple values in a single variable.

Lists can store different types of data and allow modification after creation, which makes them one of the most commonly used data structures in Python.

---

# 📝 Creating a List

A list is created using square brackets `[]`.

Example:

```python
numbers = [10, 20, 30, 40]

print(numbers)
```

### 📤 Output

```text
[10, 20, 30, 40]
```

---

# ✨ Features of Lists

- 📋 Ordered collection
- 🔄 Mutable (can be changed)
- 🔁 Allows duplicate values
- 📦 Can store different data types
- ✂️ Supports indexing and slicing
- 📏 Dynamic size

---

# 📦 Different Ways to Create Lists

## Empty List

```python
items = []

print(items)
```

Output:

```text
[]
```

---

## List with Multiple Values

```python
fruits = ["apple", "banana", "mango"]

print(fruits)
```

Output:

```text
['apple', 'banana', 'mango']
```

---

## List with Different Data Types

```python
data = ["Python", 100, 5.5, True]

print(data)
```

Output:

```text
['Python', 100, 5.5, True]
```

---

# 🔢 List Indexing

Each element in a list has an index position.

Example:

```python
languages = ["Python", "Java", "C++"]

print(languages[0])
print(languages[1])
```

Output:

```text
Python
Java
```

---

# 🔙 Negative Indexing

Negative indexing starts from the end of the list.

Example:

```python
languages = ["Python", "Java", "C++"]

print(languages[-1])
```

Output:

```text
C++
```

---

# ✂️ List Slicing

Slicing is used to access a range of elements.

Syntax:

```python
list[start:end:step]
```

Example:

```python
numbers = [1, 2, 3, 4, 5]

print(numbers[1:4])
```

Output:

```text
[2, 3, 4]
```

---

# 🔄 Modifying List Elements

Lists are mutable, so values can be changed.

Example:

```python
colors = ["red", "blue", "green"]

colors[1] = "yellow"

print(colors)
```

Output:

```text
['red', 'yellow', 'green']
```

---

# ➕ Adding Elements

## append()

Adds an element at the end of the list.

```python
numbers = [1, 2, 3]

numbers.append(4)

print(numbers)
```

Output:

```text
[1, 2, 3, 4]
```

---

## insert()

Adds an element at a specific position.

```python
numbers = [1, 3]

numbers.insert(1, 2)

print(numbers)
```

Output:

```text
[1, 2, 3]
```

---

## extend()

Adds multiple elements to a list.

```python
numbers = [1, 2]

numbers.extend([3, 4])

print(numbers)
```

Output:

```text
[1, 2, 3, 4]
```

---

# ❌ Removing Elements

## remove()

Removes a specific value.

```python
numbers = [10, 20, 30]

numbers.remove(20)

print(numbers)
```

Output:

```text
[10, 30]
```

---

## pop()

Removes an element using index.

```python
numbers = [10, 20, 30]

numbers.pop()

print(numbers)
```

Output:

```text
[10, 20]
```

---

## clear()

Removes all elements.

```python
numbers = [1, 2, 3]

numbers.clear()

print(numbers)
```

Output:

```text
[]
```

---

# 🔍 Checking Elements

Using `in` operator:

```python
fruits = ["apple", "banana"]

print("apple" in fruits)
```

Output:

```text
True
```

---

# 📏 List Length

Using `len()`:

```python
numbers = [1, 2, 3, 4]

print(len(numbers))
```

Output:

```text
4
```

---

# 🔁 Looping Through Lists

Example:

```python
fruits = ["apple", "banana", "mango"]

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

# ⚡ List Comprehension

List comprehension provides a shorter way to create lists.

Example:

```python
numbers = [x for x in range(5)]

print(numbers)
```

Output:

```text
[0, 1, 2, 3, 4]
```

---

# ⚖️ Mutable Nature of Lists

Lists can be changed after creation.

Example:

```python
numbers = [1, 2, 3]

numbers.append(4)

print(numbers)
```

Output:

```text
[1, 2, 3, 4]
```

---

# 📊 List vs Tuple

| List 📋 | Tuple 📦 |
|---|---|
| Mutable | Immutable |
| Uses `[]` | Uses `()` |
| More memory | Less memory |
| Slower | Faster |

---

# 🎯 Important List Concepts

- Creating lists
- Indexing and slicing
- Adding elements
- Removing elements
- Updating values
- Iterating through lists
- List comprehension

---

# 🚀 Summary

Python lists are powerful collections used to store and manage multiple values.

Lists are important because they allow developers to:

✅ Store multiple items  
✅ Modify data easily  
✅ Perform searching and sorting  
✅ Handle collections efficiently  

📋 Lists are one of the most important topics for Python programming and interviews.

🐍 Keep learning Python!

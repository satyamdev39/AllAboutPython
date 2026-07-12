# 📚 Python Dictionaries

A **dictionary** is a built-in Python data structure used to store data in **key-value pairs**.

Each key is unique and is used to access its corresponding value.

Example:

```python
student = {
    "name": "John",
    "age": 20,
    "course": "Python"
}

print(student)
```

### 📤 Output:

```text
{'name': 'John', 'age': 20, 'course': 'Python'}
```

---

# ✨ Features of Dictionaries

- 🔑 Stores data in key-value pairs
- 🔄 Mutable (can be changed)
- 🚫 Keys must be unique
- 📦 Values can have duplicate data
- ⚡ Fast data access using keys
- 📚 Can store different data types

---

# 📝 Creating a Dictionary

## Empty Dictionary

```python
data = {}

print(data)
```

Output:

```text
{}
```

---

## Dictionary with Values

```python
person = {
    "name": "Alice",
    "age": 25
}

print(person)
```

Output:

```text
{'name': 'Alice', 'age': 25}
```

---

# 🔑 Accessing Dictionary Values

Values are accessed using keys.

Example:

```python
student = {
    "name": "John",
    "age": 20
}

print(student["name"])
```

Output:

```text
John
```

---

# 🔍 Accessing Values Using get()

The `get()` method returns the value of a key.

Example:

```python
student = {
    "name": "John"
}

print(student.get("name"))
```

Output:

```text
John
```

If the key does not exist:

```python
print(student.get("age"))
```

Output:

```text
None
```

---

# ✏️ Adding and Updating Values

Dictionaries are mutable, so values can be changed.

Example:

```python
student = {
    "name": "John"
}

student["age"] = 20

print(student)
```

Output:

```text
{'name': 'John', 'age': 20}
```

---

# 🔄 Updating Existing Values

Example:

```python
student = {
    "name": "John",
    "age": 20
}

student["age"] = 21

print(student)
```

Output:

```text
{'name': 'John', 'age': 21}
```

---

# ❌ Removing Dictionary Elements

## pop()

Removes a key and returns its value.

```python
student = {
    "name": "John",
    "age": 20
}

student.pop("age")

print(student)
```

Output:

```text
{'name': 'John'}
```

---

## popitem()

Removes the last inserted item.

```python
student = {
    "name": "John",
    "age": 20
}

student.popitem()

print(student)
```

Output:

```text
{'name': 'John'}
```

---

## clear()

Removes all elements.

```python
student = {
    "name": "John"
}

student.clear()

print(student)
```

Output:

```text
{}
```

---

# 🔑 Dictionary Keys and Values

## keys()

Returns all keys.

```python
student = {
    "name": "John",
    "age": 20
}

print(student.keys())
```

Output:

```text
dict_keys(['name', 'age'])
```

---

## values()

Returns all values.

```python
print(student.values())
```

Output:

```text
dict_values(['John', 20])
```

---

## items()

Returns key-value pairs.

```python
print(student.items())
```

Output:

```text
dict_items([('name', 'John'), ('age', 20)])
```

---

# 🔁 Looping Through Dictionaries

## Loop Through Keys

```python
student = {
    "name": "John",
    "age": 20
}

for key in student:
    print(key)
```

Output:

```text
name
age
```

---

## Loop Through Values

```python
for value in student.values():
    print(value)
```

Output:

```text
John
20
```

---

## Loop Through Key and Value

```python
for key, value in student.items():
    print(key, value)
```

Output:

```text
name John
age 20
```

---

# 📦 Nested Dictionaries

A dictionary can contain another dictionary.

Example:

```python
students = {
    "student1": {
        "name": "John",
        "age": 20
    }
}

print(students["student1"]["name"])
```

Output:

```text
John
```

---

# 🔍 Checking Key Exists

Using `in` operator:

```python
student = {
    "name": "John"
}

print("name" in student)
```

Output:

```text
True
```

---

# 📊 Dictionary vs List

| Dictionary 📚 | List 📋 |
|---|---|
| Stores key-value pairs | Stores values only |
| Uses `{}` | Uses `[]` |
| Access using keys | Access using indexes |
| Faster searching | Slower searching |

---

# 🎯 Important Dictionary Concepts

- Creating dictionaries
- Keys and values
- Adding and updating data
- Removing elements
- Dictionary methods
- Nested dictionaries
- Looping through dictionaries

---

# 🚀 Summary

Python dictionaries are powerful data structures used to store and manage data using key-value pairs.

Important points:

✅ Mutable  
✅ Fast data access  
✅ Unique keys  
✅ Flexible values  
✅ Used widely in real-world applications  

📚 Dictionaries are one of the most important topics for Python programming and interviews. 🐍

# 📚 Python Dictionary Methods

Python dictionaries provide built-in methods to add, remove, access, and manipulate key-value pairs.

---

# 🔍 1. get()

Returns the value of a specified key.

### Syntax:

```python
dictionary.get(key)
```

Example:

```python
student = {
    "name": "John",
    "age": 20
}

print(student.get("name"))
```

Output:

```text
John
```

If the key does not exist:

```python
print(student.get("marks"))
```

Output:

```text
None
```

---

# 🔑 2. keys()

Returns all keys from a dictionary.

Example:

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

# 📦 3. values()

Returns all values from a dictionary.

Example:

```python
print(student.values())
```

Output:

```text
dict_values(['John', 20])
```

---

# 🔄 4. items()

Returns all key-value pairs.

Example:

```python
print(student.items())
```

Output:

```text
dict_items([('name', 'John'), ('age', 20)])
```

---

# ✏️ 5. update()

Updates dictionary with new key-value pairs.

Example:

```python
student = {
    "name": "John"
}

student.update({
    "age": 20
})

print(student)
```

Output:

```text
{'name': 'John', 'age': 20}
```

---

# ➕ 6. setdefault()

Returns the value of a key.

If the key does not exist, it adds the key with a value.

Example:

```python
student = {
    "name": "John"
}

student.setdefault("age", 20)

print(student)
```

Output:

```text
{'name': 'John', 'age': 20}
```

---

# ❌ 7. pop()

Removes a key and returns its value.

Example:

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

# ❌ 8. popitem()

Removes the last inserted key-value pair.

Example:

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

# 🗑️ 9. clear()

Removes all items from dictionary.

Example:

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

# 📋 10. copy()

Creates a copy of dictionary.

Example:

```python
student = {
    "name": "John"
}

new_student = student.copy()

print(new_student)
```

Output:

```text
{'name': 'John'}
```

---

# 🏗️ 11. fromkeys()

Creates a dictionary from given keys.

Example:

```python
keys = ["name", "age"]

student = dict.fromkeys(keys)

print(student)
```

Output:

```text
{'name': None, 'age': None}
```

---

# 📊 Dictionary Methods Summary

| Method | Purpose |
|---|---|
| get() | Access value |
| keys() | Get all keys |
| values() | Get all values |
| items() | Get key-value pairs |
| update() | Update dictionary |
| setdefault() | Add default value |
| pop() | Remove key |
| popitem() | Remove last item |
| clear() | Empty dictionary |
| copy() | Copy dictionary |
| fromkeys() | Create dictionary |

---

# 🚀 Summary

Dictionary methods help us:

✅ Access data  
✅ Update values  
✅ Remove items  
✅ Copy dictionaries  
✅ Manage key-value pairs  

Mastering dictionary methods is important for Python development and interviews. 🐍

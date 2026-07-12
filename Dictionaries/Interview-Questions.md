# 🎯 Python Dictionary Interview Questions & Answers

---

# 1. What is a dictionary in Python?

### ✅ Answer:

A dictionary is a collection of data stored in key-value pairs.

Example:

```python
student = {
"name":"John",
"age":20
}
```

---

# 2. Are dictionaries mutable?

### ✅ Answer:

Yes, dictionaries are mutable.

Values can be added, updated, or removed after creation.

---

# 3. Are dictionary keys unique?

### ✅ Answer:

Yes, dictionary keys must be unique.

Example:

```python
data = {
"name":"John",
"name":"Alex"
}
```

Output:

```text
{'name':'Alex'}
```

The latest value replaces the old one.

---

# 4. Can dictionary keys have different data types?

### ✅ Answer:

Yes, keys can be different immutable data types.

Example:

```python
data = {
1:"number",
"two":2
}
```

---

# 5. Can lists be dictionary keys?

### ✅ Answer:

No.

Lists are mutable, so they cannot be used as keys.

---

# 6. Difference between keys() and values()?

### ✅ Answer:

`keys()` returns all keys.

`values()` returns all values.

---

# 7. Difference between get() and []?

### ✅ Answer:

`get()` returns None if key is missing.

`[]` gives KeyError.

---

# 8. How to merge two dictionaries?

### ✅ Answer:

Using update():

```python
dict1.update(dict2)
```

---

# 9. What is a nested dictionary?

### ✅ Answer:

A dictionary inside another dictionary.

Example:

```python
student={
"class":{
"name":"John"
}
}
```

---

# 10. Difference between list and dictionary?

| List | Dictionary |
|---|---|
| Uses index | Uses keys |
| Ordered values | Key-value pairs |
| Slower searching | Faster searching |

---

# 11. What are dictionary methods?

### ✅ Answer:

Common methods:

- get()
- keys()
- values()
- items()
- update()
- pop()

---

# 12. How do you loop through a dictionary?

```python
for key,value in data.items():
    print(key,value)
```

---

# 13. How to check if a key exists?

```python
if "name" in dictionary:
    print("Exists")
```

---

# 14. Can dictionary values be duplicated?

### ✅ Answer:

Yes, values can have duplicates.

---

# 15. Why are dictionaries fast?

### ✅ Answer:

Because Python dictionaries use hashing, which allows fast key lookup.

---

# ⭐ Summary

Important dictionary interview topics:

✅ Key-value pairs  
✅ Dictionary methods  
✅ Mutable nature  
✅ Nested dictionaries  
✅ Looping  
✅ Coding problems  

📚 Dictionaries are one of the most important Python topics for interviews. 🐍

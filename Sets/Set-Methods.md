# 🔹 Python Set Methods

Sets provide built-in methods to add, remove, and perform mathematical operations on collections of unique elements.

---

# ➕ 1. add()

Adds a single element to the set.

### Syntax:

```python
set.add(element)
```

### Example:

```python
numbers = {1, 2, 3}

numbers.add(4)

print(numbers)
```

Output:

```text
{1, 2, 3, 4}
```

---

# 🔄 2. update()

Adds multiple elements to a set.

Example:

```python
numbers = {1, 2}

numbers.update([3, 4, 5])

print(numbers)
```

Output:

```text
{1, 2, 3, 4, 5}
```

---

# ❌ 3. remove()

Removes a specified element.

Example:

```python
numbers = {1, 2, 3}

numbers.remove(2)

print(numbers)
```

Output:

```text
{1, 3}
```

⚠️ Gives an error if element does not exist.

---

# 🗑️ 4. discard()

Removes an element without giving an error.

Example:

```python
numbers = {1, 2, 3}

numbers.discard(5)

print(numbers)
```

Output:

```text
{1, 2, 3}
```

---

# 🎲 5. pop()

Removes and returns a random element.

Example:

```python
numbers = {10, 20, 30}

numbers.pop()

print(numbers)
```

---

# 🧹 6. clear()

Removes all elements from a set.

Example:

```python
numbers = {1, 2, 3}

numbers.clear()

print(numbers)
```

Output:

```text
set()
```

---

# 🔗 7. union()

Returns all unique elements from both sets.

Example:

```python
a = {1,2,3}
b = {3,4,5}

print(a.union(b))
```

Output:

```text
{1,2,3,4,5}
```

---

# 🤝 8. intersection()

Returns common elements between sets.

Example:

```python
a = {1,2,3}
b = {2,3,4}

print(a.intersection(b))
```

Output:

```text
{2,3}
```

---

# ➖ 9. difference()

Returns elements present in first set but not second.

Example:

```python
a = {1,2,3}
b = {2,3,4}

print(a.difference(b))
```

Output:

```text
{1}
```

---

# 🔄 10. symmetric_difference()

Returns elements that are different in both sets.

Example:

```python
a = {1,2,3}
b = {2,3,4}

print(a.symmetric_difference(b))
```

Output:

```text
{1,4}
```

---

# ⚖️ 11. issubset()

Checks whether one set is a subset of another.

Example:

```python
a = {1,2}
b = {1,2,3}

print(a.issubset(b))
```

Output:

```text
True
```

---

# 📦 12. issuperset()

Checks whether a set contains another set.

Example:

```python
a = {1,2,3}
b = {1,2}

print(a.issuperset(b))
```

Output:

```text
True
```

---

# 🔍 13. isdisjoint()

Checks if two sets have no common elements.

Example:

```python
a = {1,2}
b = {3,4}

print(a.isdisjoint(b))
```

Output:

```text
True
```

---

# 📋 Set Methods Summary

| Method | Description |
|---|---|
| add() | Add one element |
| update() | Add multiple elements |
| remove() | Remove element |
| discard() | Remove safely |
| pop() | Remove random element |
| clear() | Empty set |
| union() | Combine sets |
| intersection() | Common elements |
| difference() | Difference between sets |
| symmetric_difference() | Unique elements |
| issubset() | Check subset |
| issuperset() | Check superset |
| isdisjoint() | Check no common values |

---

# 🚀 Summary

Set methods help in:

✅ Removing duplicates  
✅ Comparing data  
✅ Performing mathematical operations  
✅ Managing unique collections  

🔹 Sets are very useful in Python problem-solving.

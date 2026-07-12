# 🔹 Python Sets

A **set** is a built-in Python data structure used to store multiple values in a single variable.

A set contains **unique elements** and does not allow duplicate values.

Example:

```python
numbers = {1, 2, 3, 4}

print(numbers)
```

### 📤 Output:

```text
{1, 2, 3, 4}
```

---

# ✨ Features of Sets

- 🔹 Unordered collection
- 🚫 Does not allow duplicate values
- 🔄 Mutable (can be changed)
- ⚡ Faster searching compared to lists
- 🔑 Elements must be immutable
- 📦 Stores multiple values

---

# 📝 Creating a Set

## Empty Set

⚠️ Empty curly braces create a dictionary, not a set.

Incorrect:

```python
data = {}
```

Correct:

```python
data = set()

print(data)
```

Output:

```text
set()
```

---

## Set with Values

```python
fruits = {"apple", "banana", "mango"}

print(fruits)
```

Output:

```text
{'apple', 'banana', 'mango'}
```

---

# 🚫 Duplicate Values in Sets

Sets automatically remove duplicates.

Example:

```python
numbers = {1, 2, 2, 3, 3}

print(numbers)
```

Output:

```text
{1, 2, 3}
```

---

# 🔄 Adding Elements

Using `add()`:

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

# ➕ Adding Multiple Elements

Using `update()`:

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

# ❌ Removing Elements

## remove()

Removes specified element.

```python
numbers = {1, 2, 3}

numbers.remove(2)

print(numbers)
```

Output:

```text
{1, 3}
```

---

## discard()

Removes element without error if element does not exist.

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

## pop()

Removes a random element.

```python
numbers = {1, 2, 3}

numbers.pop()

print(numbers)
```

---

## clear()

Removes all elements.

```python
numbers.clear()

print(numbers)
```

Output:

```text
set()
```

---

# 🔍 Checking Elements

Using `in` operator:

```python
fruits = {"apple", "banana"}

print("apple" in fruits)
```

Output:

```text
True
```

---

# 🔁 Looping Through Sets

Example:

```python
fruits = {"apple", "banana", "mango"}

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

# 🔗 Set Operations

## Union (|)

Combines two sets.

```python
a = {1,2,3}
b = {3,4,5}

print(a | b)
```

Output:

```text
{1,2,3,4,5}
```

---

## Intersection (&)

Returns common elements.

```python
print(a & b)
```

Output:

```text
{3}
```

---

## Difference (-)

Returns elements present in first set only.

```python
print(a - b)
```

Output:

```text
{1,2}
```

---

## Symmetric Difference (^)

Returns elements that are different in both sets.

```python
print(a ^ b)
```

Output:

```text
{1,2,4,5}
```

---

# 📊 Set vs List

| Set 🔹 | List 📋 |
|---|---|
| Unordered | Ordered |
| No duplicates | Allows duplicates |
| Uses `{}` | Uses `[]` |
| Faster searching | Slower searching |
| No indexing | Supports indexing |

---

# 📊 Set vs Dictionary

| Set 🔹 | Dictionary 📚 |
|---|---|
| Stores values | Stores key-value pairs |
| Unique elements | Unique keys |
| No key-value relationship | Has keys and values |

---

# 🎯 Important Set Concepts

- Creating sets
- Adding elements
- Removing elements
- Set methods
- Union
- Intersection
- Difference
- Frozen sets

---

# 🚀 Summary

Sets are useful when we need:

✅ Unique data  
✅ Fast searching  
✅ Mathematical operations  
✅ Removing duplicates  

Sets are commonly used in Python programming and interviews. 🔹🐍

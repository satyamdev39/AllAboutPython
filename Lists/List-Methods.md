# 📋 Python List Methods

Python provides many built-in methods to work with lists. These methods help us to add, remove, modify, search, and organize list elements.

⚠️ **Note:** Lists are mutable, so most list methods modify the original list.

---

# ➕ 1. Adding Elements

## 🔹 `append()`

Adds an element at the end of the list.

Example:

```python
numbers = [1, 2, 3]

numbers.append(4)

print(numbers)
```

### 📤 Output

```text
[1, 2, 3, 4]
```

---

## 🔹 `insert()`

Adds an element at a specific index.

Syntax:

```python
list.insert(index, value)
```

Example:

```python
numbers = [1, 3]

numbers.insert(1, 2)

print(numbers)
```

### 📤 Output

```text
[1, 2, 3]
```

---

## 🔹 `extend()`

Adds elements from another iterable to the end of the list.

Example:

```python
numbers = [1, 2]

numbers.extend([3, 4, 5])

print(numbers)
```

### 📤 Output

```text
[1, 2, 3, 4, 5]
```

---

# ❌ 2. Removing Elements

## 🔹 `remove()`

Removes the first occurrence of a value.

Example:

```python
numbers = [10, 20, 30]

numbers.remove(20)

print(numbers)
```

### 📤 Output

```text
[10, 30]
```

---

## 🔹 `pop()`

Removes and returns an element using index.

Example:

```python
numbers = [10, 20, 30]

value = numbers.pop(1)

print(value)
print(numbers)
```

### 📤 Output

```text
20
[10, 30]
```

If no index is provided, it removes the last element.

```python
numbers.pop()
```

---

## 🔹 `clear()`

Removes all elements from the list.

Example:

```python
numbers = [1, 2, 3]

numbers.clear()

print(numbers)
```

### 📤 Output

```text
[]
```

---

# 🔍 3. Searching Methods

## 🔹 `index()`

Returns the index of the first occurrence of a value.

Example:

```python
fruits = ["apple", "banana", "mango"]

print(fruits.index("banana"))
```

### 📤 Output

```text
1
```

---

## 🔹 `count()`

Counts how many times an element appears.

Example:

```python
numbers = [1, 2, 2, 3, 2]

print(numbers.count(2))
```

### 📤 Output

```text
3
```

---

# 🔄 4. Sorting and Reversing

## 🔹 `sort()`

Sorts the list in ascending order.

Example:

```python
numbers = [5, 2, 8, 1]

numbers.sort()

print(numbers)
```

### 📤 Output

```text
[1, 2, 5, 8]
```

---

### Descending Order

```python
numbers = [5, 2, 8, 1]

numbers.sort(reverse=True)

print(numbers)
```

Output:

```text
[8, 5, 2, 1]
```

---

## 🔹 `reverse()`

Reverses the order of elements.

Example:

```python
numbers = [1, 2, 3, 4]

numbers.reverse()

print(numbers)
```

### 📤 Output

```text
[4, 3, 2, 1]
```

---

# 📄 5. Copying Lists

## 🔹 `copy()`

Creates a shallow copy of a list.

Example:

```python
numbers = [1, 2, 3]

new_numbers = numbers.copy()

print(new_numbers)
```

### 📤 Output

```text
[1, 2, 3]
```

---

# 🔢 6. Useful Built-in Functions with Lists

## 🔹 `len()`

Returns the number of elements.

```python
numbers = [10, 20, 30]

print(len(numbers))
```

Output:

```text
3
```

---

## 🔹 `max()`

Returns the largest value.

```python
numbers = [10, 50, 20]

print(max(numbers))
```

Output:

```text
50
```

---

## 🔹 `min()`

Returns the smallest value.

```python
numbers = [10, 50, 20]

print(min(numbers))
```

Output:

```text
10
```

---

## 🔹 `sum()`

Returns the sum of numeric values.

```python
numbers = [10, 20, 30]

print(sum(numbers))
```

Output:

```text
60
```

---

# 📊 Complete List Methods Summary

| Method | Description |
|---|---|
| `append()` | Add element at end |
| `insert()` | Add element at specific position |
| `extend()` | Add multiple elements |
| `remove()` | Remove specific value |
| `pop()` | Remove element by index |
| `clear()` | Remove all elements |
| `index()` | Find position |
| `count()` | Count occurrences |
| `sort()` | Sort list |
| `reverse()` | Reverse list |
| `copy()` | Copy list |

---

# 🎯 Interview Quick Questions

## 1. Difference between append() and extend()?

### ✅ Answer:

`append()` adds one element.

```python
list.append([3,4])
```

Result:

```text
[1,2,[3,4]]
```

`extend()` adds elements individually.

```python
list.extend([3,4])
```

Result:

```text
[1,2,3,4]
```

---

## 2. Difference between remove() and pop()?

### ✅ Answer:

- `remove()` removes by value.
- `pop()` removes by index and returns the removed value.

---

## 3. Does sort() create a new list?

### ✅ Answer:

No. `sort()` modifies the original list.

---

## 4. How to reverse a list?

### ✅ Answer:

Using:

```python
list.reverse()
```

or slicing:

```python
list[::-1]
```

---

# 🚀 Summary

Important list methods:

✅ Adding elements  
✅ Removing elements  
✅ Searching values  
✅ Sorting data  
✅ Copying lists  

Mastering list methods is essential for Python programming and interview preparation. 📋🐍

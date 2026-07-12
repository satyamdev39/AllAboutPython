# 🎯 Python Lists Interview Questions & Answers

A collection of commonly asked Python list interview questions for beginners and developers.

---

# 📋 Basic List Questions

## 1. What is a list in Python?

### ✅ Answer:

A list is a built-in Python data structure used to store multiple values in a single variable.

Lists are:

- Ordered
- Mutable
- Allow duplicate values
- Can store different data types

Example:

```python
numbers = [1, 2, 3, 4]
```

---

## 2. How do you create a list in Python?

### ✅ Answer:

Lists are created using square brackets `[]`.

Example:

```python
fruits = ["apple", "banana", "mango"]
```

---

## 3. Are lists mutable or immutable?

### ✅ Answer:

Lists are **mutable**, which means their elements can be changed after creation.

Example:

```python
numbers = [1, 2, 3]

numbers[0] = 10

print(numbers)
```

Output:

```text
[10, 2, 3]
```

---

## 4. Can a list store different data types?

### ✅ Answer:

Yes, Python lists can store multiple data types.

Example:

```python
data = ["Python", 10, 5.5, True]
```

---

## 5. Can lists contain duplicate values?

### ✅ Answer:

Yes, lists allow duplicate values.

Example:

```python
numbers = [1, 2, 2, 3]

print(numbers)
```

Output:

```text
[1, 2, 2, 3]
```

---

# 🔢 List Indexing and Slicing

## 6. What is list indexing?

### ✅ Answer:

Indexing is used to access individual elements from a list.

Example:

```python
languages = ["Python", "Java"]

print(languages[0])
```

Output:

```text
Python
```

---

## 7. What is negative indexing in lists?

### ✅ Answer:

Negative indexing accesses elements from the end of the list.

Example:

```python
numbers = [10, 20, 30]

print(numbers[-1])
```

Output:

```text
30
```

---

## 8. What is list slicing?

### ✅ Answer:

List slicing is used to extract a portion of a list.

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

# 🔄 List Methods Questions

## 9. Difference between append() and extend()?

### ✅ Answer:

`append()` adds a single element.

Example:

```python
numbers = [1, 2]

numbers.append([3, 4])

print(numbers)
```

Output:

```text
[1, 2, [3, 4]]
```

`extend()` adds elements individually.

Example:

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

## 10. Difference between remove() and pop()?

### ✅ Answer:

| remove() | pop() |
|---|---|
| Removes by value | Removes by index |
| Does not return value | Returns removed value |

Example:

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

## 11. Difference between sort() and sorted()?

### ✅ Answer:

`sort()` changes the original list.

Example:

```python
numbers = [3, 1, 2]

numbers.sort()
```

`sorted()` creates a new sorted list.

Example:

```python
numbers = [3, 1, 2]

new_list = sorted(numbers)
```

---

## 12. What is the difference between clear() and del?

### ✅ Answer:

`clear()` removes all elements but keeps the list.

```python
numbers.clear()
```

`del` can delete the entire list.

```python
del numbers
```

---

# 🧠 Intermediate List Questions

## 13. What is list comprehension?

### ✅ Answer:

List comprehension is a shorter way to create lists.

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

## 14. How do you copy a list?

### ✅ Answer:

Using:

### copy()

```python
new_list = old_list.copy()
```

### Slicing

```python
new_list = old_list[:]
```

---

## 15. Difference between shallow copy and deep copy?

### ✅ Answer:

**Shallow Copy:**
- Creates a new object
- Nested objects share references

**Deep Copy:**
- Creates completely independent objects
- Uses `copy.deepcopy()`

---

## 16. How do you remove duplicates from a list?

### ✅ Answer:

Using set:

```python
numbers = [1, 2, 2, 3]

result = list(set(numbers))

print(result)
```

Output:

```text
[1, 2, 3]
```

---

## 17. How do you reverse a list?

### ✅ Answer:

Using `reverse()`:

```python
numbers.reverse()
```

or slicing:

```python
numbers[::-1]
```

---

## 18. What is a nested list?

### ✅ Answer:

A list inside another list is called a nested list.

Example:

```python
matrix = [
    [1,2],
    [3,4]
]
```

---

# 💻 Coding Interview Questions

## 19. Find the largest element in a list.

```python
numbers = [10, 50, 20]

print(max(numbers))
```

Output:

```text
50
```

---

## 20. Reverse a list without using reverse()

```python
numbers = [1, 2, 3]

print(numbers[::-1])
```

Output:

```text
[3, 2, 1]
```

---

## 21. Find duplicate elements in a list.

```python
numbers = [1, 2, 2, 3]

for num in numbers:
    if numbers.count(num) > 1:
        print(num)
```

---

## 22. Find the second largest number.

```python
numbers = [10, 50, 30, 20]

numbers.sort()

print(numbers[-2])
```

Output:

```text
30
```

---

## 23. How to check if a list is empty?

### ✅ Answer:

Using `if not`.

Example:

```python
numbers = []

if not numbers:
    print("Empty")
```

Output:

```text
Empty
```

---

## 24. Difference between list and tuple?

### ✅ Answer:

| List 📋 | Tuple 📦 |
|---|---|
| Mutable | Immutable |
| Uses `[]` | Uses `()` |
| More memory | Less memory |
| Slower | Faster |

---

## 25. Why are lists important in Python?

### ✅ Answer:

Lists are important because they help store and manage collections of data efficiently.

They are widely used in:

- Data processing
- Algorithms
- Web development
- Data science

---

# ⭐ Summary

Important list interview topics:

✅ List creation  
✅ Indexing and slicing  
✅ List methods  
✅ Mutable nature  
✅ List comprehension  
✅ Copying lists  
✅ Coding problems  

📋 Mastering lists is essential for Python interviews and problem-solving.

🐍 Keep practicing!

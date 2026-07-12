# 🎯 Python Tuple Interview Questions & Answers

A collection of commonly asked Python tuple interview questions for beginners and developers.

---

# 📦 Basic Tuple Questions

## 1. What is a tuple in Python?

### ✅ Answer:

A tuple is a built-in Python data structure used to store multiple values in a single variable.

Tuples are:

- 📦 Ordered
- 🔒 Immutable
- 🔁 Allow duplicate values
- 📚 Can store different data types

Example:

```python
numbers = (10, 20, 30)
```

---

## 2. How do you create a tuple in Python?

### ✅ Answer:

Tuples are created using parentheses `()`.

Example:

```python
fruits = ("apple", "banana", "mango")
```

---

## 3. What is the difference between a list and a tuple?

### ✅ Answer:

| List 📋 | Tuple 📦 |
|---|---|
| Mutable | Immutable |
| Uses `[]` | Uses `()` |
| More memory | Less memory |
| Slower | Faster |
| More methods | Fewer methods |

---

## 4. Are tuples mutable or immutable?

### ✅ Answer:

Tuples are **immutable**, which means their elements cannot be changed after creation.

Example:

```python
numbers = (1, 2, 3)

numbers[0] = 10
```

Output:

```text
TypeError
```

---

## 5. Can a tuple contain different data types?

### ✅ Answer:

Yes, tuples can store different types of values.

Example:

```python
data = ("Python", 10, 5.5, True)
```

---

## 6. Can tuples contain duplicate values?

### ✅ Answer:

Yes, tuples allow duplicate values.

Example:

```python
numbers = (1, 2, 2, 3)
```

---

# 🔢 Tuple Indexing and Slicing

## 7. How do you access elements in a tuple?

### ✅ Answer:

Using indexing.

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

## 8. What is negative indexing in tuples?

### ✅ Answer:

Negative indexing accesses elements from the end.

Example:

```python
numbers = (10, 20, 30)

print(numbers[-1])
```

Output:

```text
30
```

---

## 9. Can we perform slicing on tuples?

### ✅ Answer:

Yes, tuples support slicing.

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

# 🔒 Tuple Immutability Questions

## 10. Why are tuples immutable?

### ✅ Answer:

Tuples are immutable because:

- 🔐 They provide data security
- ⚡ They are faster than lists
- 💾 They use less memory
- 🗝️ They can be used as dictionary keys

---

## 11. How can you modify a tuple?

### ✅ Answer:

Convert tuple into a list, modify it, then convert it back.

Example:

```python
numbers = (1, 2, 3)

temp = list(numbers)

temp.append(4)

numbers = tuple(temp)

print(numbers)
```

Output:

```text
(1, 2, 3, 4)
```

---

# 🔍 Tuple Methods Questions

## 12. How many methods are available for tuples?

### ✅ Answer:

Python tuples have only two built-in methods:

1. `count()`
2. `index()`

---

## 13. What does count() do in tuples?

### ✅ Answer:

`count()` returns the number of times a value appears.

Example:

```python
numbers = (1, 2, 2, 3)

print(numbers.count(2))
```

Output:

```text
2
```

---

## 14. What does index() do in tuples?

### ✅ Answer:

`index()` returns the position of the first occurrence of a value.

Example:

```python
numbers = (10, 20, 30)

print(numbers.index(20))
```

Output:

```text
1
```

---

# 🧠 Intermediate Tuple Questions

## 15. What is tuple packing?

### ✅ Answer:

Creating a tuple without using parentheses is called tuple packing.

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

## 16. What is tuple unpacking?

### ✅ Answer:

Extracting tuple values into separate variables.

Example:

```python
student = ("John", 20)

name, age = student

print(name)
```

Output:

```text
John
```

---

## 17. Can we delete a tuple?

### ✅ Answer:

Yes, we can delete the complete tuple using `del`.

Example:

```python
numbers = (1, 2, 3)

del numbers
```

---

## 18. Can a tuple have one element?

### ✅ Answer:

Yes, but a comma is required.

Incorrect:

```python
number = (10)
```

Correct:

```python
number = (10,)
```

---

## 19. Can tuples be used as dictionary keys?

### ✅ Answer:

Yes, because tuples are immutable.

Example:

```python
data = {
    (1,2): "value"
}
```

---

## 20. Difference between tuple and set?

### ✅ Answer:

| Tuple 📦 | Set 🔹 |
|---|---|
| Ordered | Unordered |
| Immutable | Mutable |
| Allows duplicates | No duplicates |
| Uses `()` | Uses `{}` |

---

# 💻 Coding Interview Questions

## 21. Reverse a tuple.

### Solution:

```python
numbers = (1, 2, 3, 4)

print(numbers[::-1])
```

Output:

```text
(4, 3, 2, 1)
```

---

## 22. Find the maximum value in a tuple.

```python
numbers = (10, 50, 20)

print(max(numbers))
```

Output:

```text
50
```

---

## 23. Remove duplicates from a tuple.

```python
numbers = (1, 2, 2, 3)

result = tuple(set(numbers))

print(result)
```

Output:

```text
(1, 2, 3)
```

---

## 24. Convert a tuple into a list.

```python
numbers = (1, 2, 3)

print(list(numbers))
```

Output:

```text
[1, 2, 3]
```

---

## 25. Why use tuples instead of lists?

### ✅ Answer:

Tuples are preferred when:

- Data should not change
- Faster access is needed
- Memory optimization is important
- Data needs to be used as dictionary keys

---

# ⭐ Summary

Important tuple interview topics:

✅ Tuple creation  
✅ Indexing and slicing  
✅ Immutability  
✅ Tuple methods  
✅ Packing and unpacking  
✅ Tuple vs List  
✅ Coding problems  

📦 Tuples are an important Python data structure and are frequently asked in interviews.

🐍 Keep practicing!

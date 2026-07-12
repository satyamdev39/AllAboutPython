# 💻 Python Tuple Programs

A collection of Python tuple-based coding problems for practice and interview preparation.

---

# 1️⃣ Create a Tuple and Print Elements

### 📝 Problem:
Create a tuple and display all elements.

### 💡 Solution:

```python
numbers = (10, 20, 30, 40)

print(numbers)
```

### 📤 Output:

```text
(10, 20, 30, 40)
```

---

# 2️⃣ Find the Length of a Tuple

### 💡 Solution:

```python
numbers = (10, 20, 30, 40)

print(len(numbers))
```

### 📤 Output:

```text
4
```

---

# 3️⃣ Access Tuple Elements Using Indexing

```python
languages = ("Python", "Java", "C++")

print(languages[0])
print(languages[2])
```

### 📤 Output:

```text
Python
C++
```

---

# 4️⃣ Access Tuple Elements Using Negative Indexing

```python
fruits = ("apple", "banana", "mango")

print(fruits[-1])
```

### 📤 Output:

```text
mango
```

---

# 5️⃣ Slice a Tuple

```python
numbers = (1, 2, 3, 4, 5)

print(numbers[1:4])
```

### 📤 Output:

```text
(2, 3, 4)
```

---

# 6️⃣ Count Occurrences of an Element

### 📝 Problem:
Find how many times an element appears in a tuple.

```python
numbers = (1, 2, 2, 3, 2, 4)

print(numbers.count(2))
```

### 📤 Output:

```text
3
```

---

# 7️⃣ Find Index of an Element

```python
languages = ("Python", "Java", "C++")

print(languages.index("Java"))
```

### 📤 Output:

```text
1
```

---

# 8️⃣ Find Maximum and Minimum Value

```python
numbers = (10, 50, 20, 5)

print(max(numbers))
print(min(numbers))
```

### 📤 Output:

```text
50
5
```

---

# 9️⃣ Find Sum of Tuple Elements

```python
numbers = (10, 20, 30)

print(sum(numbers))
```

### 📤 Output:

```text
60
```

---

# 🔟 Reverse a Tuple

### Method 1: Using Slicing

```python
numbers = (1, 2, 3, 4)

reverse = numbers[::-1]

print(reverse)
```

### 📤 Output:

```text
(4, 3, 2, 1)
```

---

# 1️⃣1️⃣ Convert Tuple into List

```python
numbers = (1, 2, 3)

list_data = list(numbers)

print(list_data)
```

### 📤 Output:

```text
[1, 2, 3]
```

---

# 1️⃣2️⃣ Convert List into Tuple

```python
numbers = [1, 2, 3]

tuple_data = tuple(numbers)

print(tuple_data)
```

### 📤 Output:

```text
(1, 2, 3)
```

---

# 1️⃣3️⃣ Join Two Tuples

```python
tuple1 = (1, 2, 3)
tuple2 = (4, 5, 6)

result = tuple1 + tuple2

print(result)
```

### 📤 Output:

```text
(1, 2, 3, 4, 5, 6)
```

---

# 1️⃣4️⃣ Repeat Tuple Elements

```python
numbers = (1, 2)

print(numbers * 3)
```

### 📤 Output:

```text
(1, 2, 1, 2, 1, 2)
```

---

# 1️⃣5️⃣ Check Element Exists in Tuple

```python
fruits = ("apple", "banana", "mango")

if "banana" in fruits:
    print("Found")
else:
    print("Not Found")
```

### 📤 Output:

```text
Found
```

---

# 1️⃣6️⃣ Find Duplicate Elements in Tuple

```python
numbers = (1, 2, 3, 2, 4, 1)

duplicates = []

for num in numbers:
    if numbers.count(num) > 1 and num not in duplicates:
        duplicates.append(num)

print(tuple(duplicates))
```

### 📤 Output:

```text
(1, 2)
```

---

# 1️⃣7️⃣ Convert Nested Tuple into List

```python
data = ((1, 2), (3, 4), (5, 6))

result = []

for item in data:
    result.extend(item)

print(result)
```

### 📤 Output:

```text
[1, 2, 3, 4, 5, 6]
```

---

# 1️⃣8️⃣ Find Even Numbers from Tuple

```python
numbers = (1, 2, 3, 4, 5, 6)

even = []

for num in numbers:
    if num % 2 == 0:
        even.append(num)

print(tuple(even))
```

### 📤 Output:

```text
(2, 4, 6)
```

---

# 1️⃣9️⃣ Tuple Unpacking Program

```python
student = ("John", 21, "Python")

name, age, course = student

print(name)
print(age)
print(course)
```

### 📤 Output:

```text
John
21
Python
```

---

# 2️⃣0️⃣ Check Two Tuples Are Equal

```python
tuple1 = (1, 2, 3)
tuple2 = (1, 2, 3)

if tuple1 == tuple2:
    print("Both tuples are equal")
else:
    print("Not equal")
```

### 📤 Output:

```text
Both tuples are equal
```

---

# 🎯 Interview Practice Problems

Try solving these yourself:

1. Find the second largest element in a tuple
2. Remove duplicate values from a tuple
3. Find common elements between two tuples
4. Convert tuple of strings into uppercase
5. Find the frequency of each element
6. Sort a tuple without using sorted()
7. Check whether a tuple is palindrome
8. Find missing numbers in a tuple
9. Merge multiple tuples
10. Find the longest tuple from a list of tuples

---

# 🚀 Summary

Tuple programs help you practice:

✅ Tuple creation  
✅ Indexing and slicing  
✅ Tuple methods  
✅ Conversion between list and tuple  
✅ Tuple operations  
✅ Problem-solving skills  

📦 Practice tuples regularly for better Python interview preparation. 🐍

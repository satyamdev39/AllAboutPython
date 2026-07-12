# 🎯 Python Basics Interview Questions & Answers

A collection of commonly asked Python interview questions for beginners and freshers.

---

# 🐍 Python Introduction Questions

## 1. What is Python?

### ✅ Answer:

Python is a **high-level, interpreted, general-purpose programming language** known for its simple syntax and readability.

It is widely used in:

- 🌐 Web Development
- 🤖 Artificial Intelligence
- 🧠 Machine Learning
- 📊 Data Science
- ⚙️ Automation

---

## 2. Who created Python?

### ✅ Answer:

Python was created by **Guido van Rossum** and was first released in **1991**.

---

## 3. Why is Python popular?

### ✅ Answer:

Python is popular because:

- 📖 Easy-to-read syntax
- ⚡ Faster development
- 📚 Large library support
- 🌍 Cross-platform
- 🤖 Used in AI and Data Science

---

## 4. What are the features of Python?

### ✅ Answer:

Main features:

- Simple and readable syntax
- Interpreted language
- Object-oriented programming support
- Open source
- Dynamically typed
- Large community support

---

# 📦 Variables Questions

## 5. What is a variable in Python?

### ✅ Answer:

A variable is a name used to store data values in memory.

Example:

```python
name = "Python"
age = 25
```

---

## 6. Does Python require variable declaration?

### ✅ Answer:

No. Python automatically determines the data type of a variable.

Example:

```python
x = 10
```

Python automatically identifies `x` as an integer.

---

## 7. What are the rules for naming variables?

### ✅ Answer:

Rules:

✅ Can contain letters, numbers, and `_`  
✅ Cannot start with a number  
✅ Cannot use keywords  
✅ Case-sensitive  

Example:

```python
student_name = "John"
```

---

## 8. Is Python case-sensitive?

### ✅ Answer:

Yes, Python is case-sensitive.

Example:

```python
name = "John"
Name = "Alex"
```

Both are different variables.

---

# 🗂️ Data Types Questions

## 9. What are Python data types?

### ✅ Answer:

Data types define the type of data stored in a variable.

Common Python data types:

- 🔢 int
- 💯 float
- 🔤 str
- 📋 list
- 📦 tuple
- 🎯 set
- 📚 dictionary
- ✅ bool

---

## 10. How do you check the data type of a variable?

### ✅ Answer:

Using the `type()` function.

Example:

```python
x = 10

print(type(x))
```

Output:

```text
<class 'int'>
```

---

## 11. What is the difference between list and tuple?

### ✅ Answer:

| List 📋 | Tuple 📦 |
|---|---|
| Mutable | Immutable |
| Uses `[]` | Uses `()` |
| Slower | Faster |
| More memory | Less memory |

---

## 12. What are mutable and immutable objects?

### ✅ Answer:

### Mutable (Can be changed):

- List
- Dictionary
- Set

### Immutable (Cannot be changed):

- String
- Tuple
- Integer

---

# ⚙️ Operators Questions

## 13. What are operators in Python?

### ✅ Answer:

Operators are symbols used to perform operations on variables and values.

Examples:

```python
+
-
*
/
==
```

---

## 14. What is the difference between `==` and `is`?

### ✅ Answer:

`==` checks whether values are equal.

`is` checks whether two variables point to the same object in memory.

Example:

```python
a = [1,2]
b = [1,2]

print(a == b)
print(a is b)
```

Output:

```text
True
False
```

---

## 15. What are logical operators in Python?

### ✅ Answer:

Logical operators are:

- `and`
- `or`
- `not`

Example:

```python
age = 20

print(age > 18 and age < 30)
```

---

# 📝 Syntax Questions

## 16. Why is indentation important in Python?

### ✅ Answer:

Python uses indentation to define blocks of code.

Example:

```python
if True:
    print("Hello")
```

Incorrect indentation causes an error.

---

## 17. What are keywords in Python?

### ✅ Answer:

Keywords are reserved words with special meanings.

Examples:

```text
if
else
for
while
class
def
return
import
```

---

## 18. What is the difference between syntax error and runtime error?

### ✅ Answer:

### Syntax Error:
Error due to incorrect code structure.

Example:

```python
print("Hello"
```

### Runtime Error:
Error that occurs during program execution.

Example:

```python
10 / 0
```

---

# 🔄 Type Conversion Questions

## 19. What is type casting?

### ✅ Answer:

Type casting is converting one data type into another.

Example:

```python
x = "100"

y = int(x)

print(y)
```

Output:

```text
100
```

---

## 20. What is dynamic typing in Python?

### ✅ Answer:

Python allows variables to change their data type during execution.

Example:

```python
x = 10

x = "Python"
```

---

# 🚀 Common Coding Interview Questions

## 21. Reverse a string

```python
text = "Python"

print(text[::-1])
```

Output:

```text
nohtyP
```

---

## 22. Check palindrome string

```python
text = "madam"

print(text == text[::-1])
```

Output:

```text
True
```

---

## 23. Find the largest number

```python
numbers = [10, 50, 20]

print(max(numbers))
```

Output:

```text
50
```

---

# ⭐ Summary

These Python basics interview questions cover:

✅ Python Introduction  
✅ Variables  
✅ Data Types  
✅ Operators  
✅ Syntax  
✅ Type Conversion  
✅ Basic Coding Problems  

Keep practicing and improve your Python skills! 🐍🚀

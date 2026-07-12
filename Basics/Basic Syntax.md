# 🐍 Python Basic Syntax

Python syntax refers to the set of rules that define how Python programs are written and executed.

Python has a simple and readable syntax compared to many other programming languages.

---

# 👋 1. First Python Program

The `print()` function is used to display output.

```python
print("Hello, Python!")
```

### 📤 Output

```text
Hello, Python!
```

---

# 📝 2. Python Comments

Comments are used to explain code. Python ignores comments during execution.

## Single Line Comment

```python
# This is a comment

print("Hello")
```

## Multi-Line Comment

```python
"""
This is a
multi-line comment
"""

print("Python")
```

---

# 📦 3. Variables

Variables are used to store data values.

Example:

```python
name = "Python"
age = 30

print(name)
print(age)
```

### 📤 Output

```text
Python
30
```

---

# 📏 4. Indentation

Python uses indentation (spaces) to define blocks of code.

Example:

```python
if 10 > 5:
    print("10 is greater")
```

### 📤 Output

```text
10 is greater
```

⚠️ Incorrect indentation will cause an error.

---

# 🔤 5. Python Identifiers

Identifiers are names used for variables, functions, classes, etc.

Example:

```python
student_name = "John"
```

## Rules:

✅ Can contain letters, numbers, and underscores  
✅ Cannot start with a number  
✅ Cannot use Python keywords  
✅ Case-sensitive  

Example:

```python
name = "Python"
Name = "Java"

print(name)
print(Name)
```

Output:

```text
Python
Java
```

---

# 🔢 6. Python Keywords

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
try
except
True
False
None
```

You cannot use keywords as variable names.

❌ Wrong:

```python
class = "Python"
```

---

# 🧮 7. Python Statements

A statement is an instruction that Python executes.

Example:

```python
x = 10
print(x)
```

---

# ➡️ 8. Multiple Statements

Multiple statements can be written on separate lines.

Example:

```python
x = 10
y = 20
print(x + y)
```

Output:

```text
30
```

---

# 📚 9. Python Blocks

A block is a group of statements with the same indentation.

Example:

```python
if True:
    print("Python")
    print("Programming")
```

Output:

```text
Python
Programming
```

---

# 🔄 10. Line Continuation

Long statements can be continued using `\`.

Example:

```python
total = 10 + 20 + \
        30 + 40

print(total)
```

Output:

```text
100
```

---

# 🔤 11. Python Case Sensitivity

Python is case-sensitive.

Example:

```python
name = "John"
Name = "Alex"

print(name)
print(Name)
```

Output:

```text
John
Alex
```

---

# 📥 12. Taking User Input

The `input()` function is used to take input from users.

Example:

```python
name = input("Enter your name: ")

print(name)
```

Output:

```text
Enter your name: John
John
```

---

# 🔄 13. Type Conversion

Changing one data type into another is called type casting.

Example:

```python
age = input("Enter age: ")

age = int(age)

print(age)
```

---

# 🐍 14. Python Execution

Python code is executed line by line.

Example:

```python
print("Start")

print("End")
```

Output:

```text
Start
End
```

---

# 🎯 Interview Questions

## 1. Why is Python called a simple language?

**Answer:**

Python has a clean syntax and requires fewer lines of code compared to many other languages.

---

## 2. Is indentation mandatory in Python?

**Answer:**

Yes, indentation is required to define blocks of code.

---

## 3. What happens if indentation is incorrect?

**Answer:**

Python raises an `IndentationError`.

---

## 4. Is Python case-sensitive?

**Answer:**

Yes, Python treats uppercase and lowercase letters differently.

Example:

```python
Name != name
```

---

## 5. What is the purpose of comments?

**Answer:**

Comments explain code and improve readability. They are ignored by the Python interpreter.

---

## 6. What is the difference between syntax error and runtime error?

**Answer:**

- Syntax Error → Error in writing code rules.
- Runtime Error → Error that occurs while executing the program.

---

# 🚀 Summary

Python basic syntax includes:

✅ Printing output  
✅ Variables  
✅ Comments  
✅ Indentation  
✅ Keywords  
✅ Statements  
✅ User input  
✅ Type conversion  

Mastering syntax is the first step toward becoming a Python developer. 🐍

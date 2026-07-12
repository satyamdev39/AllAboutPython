# 🎯 Python String Interview Questions & Answers

A collection of commonly asked Python string interview questions for beginners and developers.

---

# 🔤 Basic String Questions

## 1. What is a string in Python?

### ✅ Answer:

A string is a sequence of characters enclosed inside single quotes (`' '`), double quotes (`" "`), or triple quotes.

Example:

```python
name = "Python"
```

---

## 2. How do you create a string in Python?

### ✅ Answer:

Strings can be created using:

### Single Quotes

```python
name = 'Python'
```

### Double Quotes

```python
name = "Python"
```

### Triple Quotes

```python
message = """Hello Python"""
```

---

## 3. Are strings mutable or immutable in Python?

### ✅ Answer:

Strings are **immutable**, which means their values cannot be changed after creation.

Example:

```python
text = "Python"

# text[0] = "J" ❌ Error
```

A new string must be created instead.

---

## 4. What is string indexing?

### ✅ Answer:

Indexing is used to access individual characters of a string.

Example:

```python
text = "Python"

print(text[0])
```

Output:

```text
P
```

Python supports:

- Positive indexing ➡️ starts from `0`
- Negative indexing ⬅️ starts from `-1`

---

## 5. What is string slicing?

### ✅ Answer:

Slicing is used to extract a part of a string.

Syntax:

```python
string[start:end:step]
```

Example:

```python
text = "Python"

print(text[0:3])
```

Output:

```text
Pyt
```

---

# 🔍 String Methods Questions

## 6. Difference between `find()` and `index()`?

### ✅ Answer:

Both are used to find the position of a substring.

| find() | index() |
|---|---|
| Returns -1 if not found | Raises ValueError |
| Safer to use | Throws error |

Example:

```python
text = "Python"

print(text.find("z"))
```

Output:

```text
-1
```

---

## 7. Difference between `split()` and `join()`?

### ✅ Answer:

`split()` converts a string into a list.

Example:

```python
text = "Python Java"

print(text.split())
```

Output:

```text
['Python', 'Java']
```

`join()` converts a list into a string.

Example:

```python
words = ["Python", "Java"]

print("-".join(words))
```

Output:

```text
Python-Java
```

---

## 8. What is the difference between `upper()` and `capitalize()`?

### ✅ Answer:

`upper()` converts all characters to uppercase.

```python
print("python".upper())
```

Output:

```text
PYTHON
```

`capitalize()` only converts the first character.

```python
print("python".capitalize())
```

Output:

```text
Python
```

---

## 9. How do you check the length of a string?

### ✅ Answer:

Using the `len()` function.

Example:

```python
text = "Python"

print(len(text))
```

Output:

```text
6
```

---

## 10. How do you check if a substring exists in a string?

### ✅ Answer:

Using membership operators:

- `in`
- `not in`

Example:

```python
text = "Python"

print("Py" in text)
```

Output:

```text
True
```

---

# 🧠 Intermediate String Questions

## 11. How do you reverse a string?

### ✅ Answer:

Using slicing:

```python
text = "Python"

print(text[::-1])
```

Output:

```text
nohtyP
```

---

## 12. How do you check whether a string is a palindrome?

### ✅ Answer:

A palindrome is a string that reads the same forward and backward.

Example:

```python
text = "madam"

print(text == text[::-1])
```

Output:

```text
True
```

---

## 13. How do you remove spaces from a string?

### ✅ Answer:

Using `replace()`:

```python
text = "Python Programming"

print(text.replace(" ", ""))
```

Output:

```text
PythonProgramming
```

---

## 14. How do you count characters in a string?

### ✅ Answer:

Using `count()`:

```python
text = "banana"

print(text.count("a"))
```

Output:

```text
3
```

---

## 15. How do you find duplicate characters in a string?

### ✅ Answer:

Example:

```python
text = "programming"

for char in text:
    if text.count(char) > 1:
        print(char)
```

---

# 🚀 Advanced String Questions

## 16. Why are strings immutable in Python?

### ✅ Answer:

Strings are immutable because:

- 🔒 They improve security
- ⚡ They allow faster performance
- 🧠 They can be used as dictionary keys
- 💾 Memory can be optimized

---

## 17. Difference between `==` and `is` for strings?

### ✅ Answer:

`==` compares string values.

`is` compares whether two variables point to the same object.

Example:

```python
a = "Python"
b = "Python"

print(a == b)
print(a is b)
```

---

## 18. What are escape characters in strings?

### ✅ Answer:

Escape characters represent special characters.

Examples:

| Escape | Meaning |
|---|---|
| `\n` | New line |
| `\t` | Tab |
| `\\` | Backslash |
| `\'` | Single quote |

Example:

```python
print("Hello\nPython")
```

Output:

```text
Hello
Python
```

---

## 19. Difference between string and list?

### ✅ Answer:

| String 🔤 | List 📋 |
|---|---|
| Stores characters | Stores multiple values |
| Immutable | Mutable |
| Uses quotes | Uses brackets |

---

## 20. What is string formatting?

### ✅ Answer:

String formatting is used to insert values into strings.

Using f-string:

```python
name = "John"
age = 25

print(f"{name} is {age} years old")
```

Output:

```text
John is 25 years old
```

---

# 💻 Coding Interview Problems

## 1. Reverse a String

```python
text = "Python"

print(text[::-1])
```

---

## 2. Count Vowels in a String

```python
text = "Python Programming"

count = 0

for char in text:
    if char.lower() in "aeiou":
        count += 1

print(count)
```

---

## 3. Check Anagram

Example:

```python
word1 = "listen"
word2 = "silent"

print(sorted(word1) == sorted(word2))
```

Output:

```text
True
```

---

## 4. Find First Non-Repeating Character

Example:

```python
text = "python"

for char in text:
    if text.count(char) == 1:
        print(char)
        break
```

---

# ⭐ Summary

Important string concepts for interviews:

✅ String creation  
✅ Indexing & slicing  
✅ String methods  
✅ Immutability  
✅ String formatting  
✅ Searching and validation  
✅ String-based coding problems  

🐍 Practice strings regularly because they are one of the most asked topics in Python interviews.

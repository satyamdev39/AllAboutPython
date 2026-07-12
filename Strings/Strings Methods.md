# 🔤 Python String Methods

Python provides many built-in methods to work with strings. These methods help us to modify, search, validate, and format string data.

⚠️ **Note:** Strings are immutable, so these methods do not change the original string. They return a new string.

---

# 🔠 1. Case Conversion Methods

## 🔹 `upper()`

Converts all characters into uppercase.

Example:

```python
text = "python"

print(text.upper())
```

### 📤 Output

```text
PYTHON
```

---

## 🔹 `lower()`

Converts all characters into lowercase.

Example:

```python
text = "PYTHON"

print(text.lower())
```

### 📤 Output

```text
python
```

---

## 🔹 `title()`

Converts the first letter of each word into uppercase.

Example:

```python
text = "python programming"

print(text.title())
```

### 📤 Output

```text
Python Programming
```

---

## 🔹 `capitalize()`

Converts the first character of a string into uppercase.

Example:

```python
text = "python"

print(text.capitalize())
```

Output:

```text
Python
```

---

## 🔹 `swapcase()`

Changes uppercase letters to lowercase and lowercase letters to uppercase.

Example:

```python
text = "PyThOn"

print(text.swapcase())
```

Output:

```text
pYtHoN
```

---

# 🔍 2. Searching Methods

## 🔹 `find()`

Returns the index of the first occurrence.

Returns `-1` if not found.

Example:

```python
text = "Python"

print(text.find("t"))
```

Output:

```text
2
```

---

## 🔹 `index()`

Works like `find()` but gives an error if the value is not found.

Example:

```python
text = "Python"

print(text.index("P"))
```

Output:

```text
0
```

---

## 🔹 `count()`

Counts how many times a value appears.

Example:

```python
text = "banana"

print(text.count("a"))
```

Output:

```text
3
```

---

## 🔹 `startswith()`

Checks whether a string starts with a specific value.

Example:

```python
text = "Python"

print(text.startswith("Py"))
```

Output:

```text
True
```

---

## 🔹 `endswith()`

Checks whether a string ends with a specific value.

Example:

```python
text = "Python"

print(text.endswith("on"))
```

Output:

```text
True
```

---

# ✂️ 3. String Modification Methods

## 🔹 `replace()`

Replaces a word or character with another value.

Example:

```python
text = "I like Java"

print(text.replace("Java", "Python"))
```

Output:

```text
I like Python
```

---

## 🔹 `strip()`

Removes spaces from both sides.

Example:

```python
text = "  Python  "

print(text.strip())
```

Output:

```text
Python
```

---

## 🔹 `lstrip()`

Removes spaces from the left side.

Example:

```python
text = "  Python"

print(text.lstrip())
```

Output:

```text
Python
```

---

## 🔹 `rstrip()`

Removes spaces from the right side.

Example:

```python
text = "Python  "

print(text.rstrip())
```

Output:

```text
Python
```

---

# 🔄 4. Splitting and Joining Methods

## 🔹 `split()`

Splits a string into a list.

Example:

```python
text = "Python is easy"

print(text.split())
```

Output:

```text
['Python', 'is', 'easy']
```

---

## 🔹 `join()`

Joins elements of a list into a string.

Example:

```python
words = ["Python", "Java", "C++"]

print("-".join(words))
```

Output:

```text
Python-Java-C++
```

---

# ✅ 5. Validation Methods

## 🔹 `isalpha()`

Checks if all characters are alphabets.

Example:

```python
text = "Python"

print(text.isalpha())
```

Output:

```text
True
```

---

## 🔹 `isdigit()`

Checks if all characters are digits.

Example:

```python
number = "123"

print(number.isdigit())
```

Output:

```text
True
```

---

## 🔹 `isalnum()`

Checks if characters contain only letters and numbers.

Example:

```python
text = "Python123"

print(text.isalnum())
```

Output:

```text
True
```

---

## 🔹 `isspace()`

Checks if string contains only spaces.

Example:

```python
text = "   "

print(text.isspace())
```

Output:

```text
True
```

---

# 📏 6. Alignment Methods

## 🔹 `center()`

Centers a string.

Example:

```python
text = "Python"

print(text.center(10, "-"))
```

Output:

```text
--Python--
```

---

## 🔹 `ljust()`

Aligns string to the left.

```python
text = "Python"

print(text.ljust(10, "-"))
```

Output:

```text
Python----
```

---

## 🔹 `rjust()`

Aligns string to the right.

```python
text = "Python"

print(text.rjust(10, "-"))
```

Output:

```text
----Python
```

---

# 🔢 7. Formatting Methods

## 🔹 `format()`

Used for inserting values into strings.

Example:

```python
name = "John"
age = 25

print("My name is {} and age is {}".format(name, age))
```

Output:

```text
My name is John and age is 25
```

---

# 📌 Important String Methods Summary

| Method | Purpose |
|---|---|
| `upper()` | Convert to uppercase |
| `lower()` | Convert to lowercase |
| `title()` | Capitalize words |
| `find()` | Search position |
| `count()` | Count occurrences |
| `replace()` | Replace text |
| `strip()` | Remove spaces |
| `split()` | Convert string to list |
| `join()` | Convert list to string |
| `startswith()` | Check starting value |
| `endswith()` | Check ending value |
| `isalpha()` | Check alphabets |
| `isdigit()` | Check digits |

---

# 🚀 Summary

String methods make it easier to:

✅ Modify text  
✅ Search data  
✅ Validate input  
✅ Format output  
✅ Convert between strings and lists  

Mastering string methods is important for Python programming and interview preparation. 🐍

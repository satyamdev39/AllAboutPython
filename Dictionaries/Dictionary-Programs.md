# 💻 Python Dictionary Programs

Practice problems based on Python dictionaries.

---

# 1️⃣ Create a Dictionary

```python
student = {
    "name": "John",
    "age": 20,
    "course": "Python"
}

print(student)
```

Output:

```text
{'name': 'John', 'age': 20, 'course': 'Python'}
```

---

# 2️⃣ Access Dictionary Values

```python
student = {
    "name": "John"
}

print(student["name"])
```

Output:

```text
John
```

---

# 3️⃣ Add New Key-Value Pair

```python
student = {
    "name": "John"
}

student["age"] = 20

print(student)
```

Output:

```text
{'name': 'John', 'age': 20}
```

---

# 4️⃣ Update Dictionary Value

```python
student = {
    "age": 20
}

student["age"] = 21

print(student)
```

Output:

```text
{'age': 21}
```

---

# 5️⃣ Delete a Key

```python
student = {
    "name": "John",
    "age": 20
}

del student["age"]

print(student)
```

Output:

```text
{'name': 'John'}
```

---

# 6️⃣ Count Frequency of Characters

```python
text = "python"

frequency = {}

for char in text:
    frequency[char] = frequency.get(char,0)+1

print(frequency)
```

Output:

```text
{'p':1,'y':1,'t':1,'h':1,'o':1,'n':1}
```

---

# 7️⃣ Find Duplicate Characters

```python
text = "programming"

frequency = {}

for char in text:
    frequency[char] = frequency.get(char,0)+1

for key,value in frequency.items():
    if value > 1:
        print(key)
```

Output:

```text
r
g
m
```

---

# 8️⃣ Merge Two Dictionaries

```python
a = {"name":"John"}
b = {"age":20}

a.update(b)

print(a)
```

Output:

```text
{'name':'John','age':20}
```

---

# 9️⃣ Find Maximum Value in Dictionary

```python
marks = {
    "Math":90,
    "Python":95,
    "Java":80
}

print(max(marks.values()))
```

Output:

```text
95
```

---

# 🔟 Sort Dictionary by Value

```python
marks = {
    "A":50,
    "B":90,
    "C":70
}

result = dict(sorted(marks.items(),
key=lambda x:x[1]))

print(result)
```

Output:

```text
{'A':50,'C':70,'B':90}
```

---

# 🎯 Interview Practice Problems

1. Find the most repeated character in a string
2. Count words in a sentence
3. Reverse keys and values
4. Remove duplicate values
5. Find common keys between dictionaries
6. Convert two lists into dictionary
7. Find student with highest marks
8. Group items using dictionary
9. Check if two dictionaries are equal
10. Create a nested dictionary

---

# 🚀 Summary

Dictionary programs improve:

✅ Data handling  
✅ Key-value operations  
✅ Searching  
✅ Counting problems  
✅ Real-world programming skills

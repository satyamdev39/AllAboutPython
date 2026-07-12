# 💻 Python List Programs

A collection of Python list-based coding problems for practice and interview preparation.

---

# 1️⃣ Find the Sum of All Elements in a List

### 📝 Problem:
Find the sum of all numbers present in a list.

### 💡 Solution:

```python
numbers = [10, 20, 30, 40]

total = sum(numbers)

print(total)
```

### 📤 Output:

```text
100
```

---

# 2️⃣ Find the Largest Element in a List

### 💡 Solution:

```python
numbers = [10, 50, 30, 20]

largest = max(numbers)

print(largest)
```

### 📤 Output:

```text
50
```

---

# 3️⃣ Find the Smallest Element in a List

```python
numbers = [10, 5, 20, 2]

smallest = min(numbers)

print(smallest)
```

### 📤 Output:

```text
2
```

---

# 4️⃣ Reverse a List

### Method 1: Using reverse()

```python
numbers = [1, 2, 3, 4]

numbers.reverse()

print(numbers)
```

Output:

```text
[4, 3, 2, 1]
```

---

### Method 2: Using Slicing

```python
numbers = [1, 2, 3, 4]

print(numbers[::-1])
```

Output:

```text
[4, 3, 2, 1]
```

---

# 5️⃣ Find the Length of a List

```python
numbers = [10, 20, 30, 40]

print(len(numbers))
```

Output:

```text
4
```

---

# 6️⃣ Remove Duplicates from a List

```python
numbers = [1, 2, 2, 3, 4, 4]

unique = list(set(numbers))

print(unique)
```

Output:

```text
[1, 2, 3, 4]
```

---

# 7️⃣ Count Occurrence of an Element

```python
numbers = [1, 2, 2, 3, 2]

count = numbers.count(2)

print(count)
```

Output:

```text
3
```

---

# 8️⃣ Find Second Largest Number

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

# 9️⃣ Merge Two Lists

```python
list1 = [1, 2, 3]
list2 = [4, 5, 6]

result = list1 + list2

print(result)
```

Output:

```text
[1, 2, 3, 4, 5, 6]
```

---

# 🔟 Find Common Elements Between Two Lists

```python
list1 = [1, 2, 3, 4]
list2 = [3, 4, 5, 6]

common = list(set(list1) & set(list2))

print(common)
```

Output:

```text
[3, 4]
```

---

# 1️⃣1️⃣ Remove Empty Strings from a List

```python
words = ["Python", "", "Java", "", "C++"]

result = [word for word in words if word]

print(result)
```

Output:

```text
['Python', 'Java', 'C++']
```

---

# 1️⃣2️⃣ Find Even Numbers from a List

```python
numbers = [1, 2, 3, 4, 5, 6]

even = []

for num in numbers:
    if num % 2 == 0:
        even.append(num)

print(even)
```

Output:

```text
[2, 4, 6]
```

---

# 1️⃣3️⃣ Find Odd Numbers from a List

```python
numbers = [1, 2, 3, 4, 5, 6]

odd = [num for num in numbers if num % 2 != 0]

print(odd)
```

Output:

```text
[1, 3, 5]
```

---

# 1️⃣4️⃣ Check if List is Empty

```python
numbers = []

if not numbers:
    print("List is empty")
else:
    print("List is not empty")
```

Output:

```text
List is empty
```

---

# 1️⃣5️⃣ Multiply All Elements of a List

```python
numbers = [2, 3, 4]

result = 1

for num in numbers:
    result *= num

print(result)
```

Output:

```text
24
```

---

# 1️⃣6️⃣ Find Frequency of Each Element

```python
numbers = [1, 2, 2, 3, 1, 2]

frequency = {}

for num in numbers:
    frequency[num] = frequency.get(num, 0) + 1

print(frequency)
```

Output:

```text
{1: 2, 2: 3, 3: 1}
```

---

# 1️⃣7️⃣ Sort a List Without Using sort()

```python
numbers = [5, 2, 8, 1]

for i in range(len(numbers)):
    for j in range(i + 1, len(numbers)):
        if numbers[i] > numbers[j]:
            numbers[i], numbers[j] = numbers[j], numbers[i]

print(numbers)
```

Output:

```text
[1, 2, 5, 8]
```

---

# 1️⃣8️⃣ Find Duplicate Elements in a List

```python
numbers = [1, 2, 3, 2, 4, 1]

duplicates = []

for num in numbers:
    if numbers.count(num) > 1 and num not in duplicates:
        duplicates.append(num)

print(duplicates)
```

Output:

```text
[1, 2]
```

---

# 1️⃣9️⃣ Rotate a List

```python
numbers = [1, 2, 3, 4, 5]

rotate = numbers[2:] + numbers[:2]

print(rotate)
```

Output:

```text
[3, 4, 5, 1, 2]
```

---

# 2️⃣0️⃣ Flatten a Nested List

```python
nested = [[1, 2], [3, 4], [5, 6]]

result = []

for item in nested:
    for value in item:
        result.append(value)

print(result)
```

Output:

```text
[1, 2, 3, 4, 5, 6]
```

---

# 🎯 Interview Practice Problems

Try solving these yourself:

1. Find the missing number in a list
2. Find all pairs with a given sum
3. Move all zeros to the end
4. Find the intersection of two lists
5. Find the maximum difference between two elements
6. Remove duplicates without using set()
7. Find the longest increasing sequence
8. Check if two lists are equal
9. Split a list into chunks
10. Find the median of a list

---

# 🚀 Summary

List problems help you practice:

✅ Loops  
✅ Conditions  
✅ List methods  
✅ Searching  
✅ Sorting  
✅ Data manipulation  

Regular practice of list programs improves problem-solving skills for Python interviews. 🐍

# 💼 Python Sets - Interview Questions & Answers

Welcome to the **Python Sets Interview Questions** guide. This document covers the most frequently asked interview questions about Python Sets, from beginner to advanced.

---

# 📚 Table of Contents

- Beginner Questions
- Intermediate Questions
- Advanced Questions
- Time Complexity
- Coding Questions
- Quick Revision

---

# 🟢 Beginner Questions

## 1. What is a Set in Python?

**Answer:**

A **Set** is an unordered, mutable collection of unique elements.

### Example

```python
numbers = {1, 2, 3, 4}
print(numbers)
```

---

## 2. What are the characteristics of a Set?

**Answer:**

- Stores unique values only
- Unordered collection
- Mutable
- Does not support indexing
- Elements must be immutable (hashable)

---

## 3. How do you create a Set?

**Answer:**

```python
fruits = {"Apple", "Banana", "Mango"}
```

---

## 4. How do you create an empty Set?

**Answer:**

```python
s = set()
```

**Note:**

```python
{}
```

creates an empty dictionary, **not** an empty set.

---

## 5. Can Sets contain duplicate values?

**Answer:**

No.

Duplicate values are automatically removed.

```python
s = {1, 2, 2, 3}

print(s)
```

**Output**

```
{1, 2, 3}
```

---

## 6. Are Sets ordered?

**Answer:**

No.

Sets are unordered, so their elements have no fixed position.

---

## 7. Can we access elements using indexing?

**Answer:**

No.

```python
s = {1,2,3}

print(s[0])
```

Produces an error because Sets do not support indexing.

---

## 8. How do you add an element?

**Answer:**

Using `add()`.

```python
s = {1,2,3}

s.add(4)
```

---

## 9. How do you add multiple elements?

**Answer:**

Using `update()`.

```python
s = {1,2}

s.update([3,4,5])
```

---

## 10. Difference between add() and update()

| add() | update() |
|--------|-----------|
| Adds one element | Adds multiple elements |
| Accepts a single value | Accepts iterable |

---

## 11. How do you remove an element?

**Answer:**

Using `remove()`.

```python
s.remove(5)
```

Raises an error if the element doesn't exist.

---

## 12. Difference between remove() and discard()

| remove() | discard() |
|------------|-------------|
| Raises KeyError | No error |
| Element must exist | Safe removal |

---

## 13. What does pop() do?

**Answer:**

Removes and returns a random element.

```python
value = s.pop()
```

---

## 14. How do you clear a Set?

```python
s.clear()
```

Removes all elements.

---

## 15. How do you delete an entire Set?

```python
del s
```

---

# 🔵 Intermediate Questions

## 16. What is Union?

**Answer:**

Combines all unique elements.

```python
A = {1,2}
B = {2,3}

print(A | B)
```

Output

```
{1,2,3}
```

---

## 17. What is Intersection?

Returns common elements.

```python
A & B
```

---

## 18. What is Difference?

Returns elements present in first set only.

```python
A - B
```

---

## 19. What is Symmetric Difference?

Returns elements that are in either set but not both.

```python
A ^ B
```

---

## 20. What is a Subset?

A set whose every element exists in another set.

```python
A.issubset(B)
```

---

## 21. What is a Superset?

Contains every element of another set.

```python
A.issuperset(B)
```

---

## 22. What are Disjoint Sets?

Sets having no common elements.

```python
A.isdisjoint(B)
```

---

## 23. What is frozenset?

An immutable version of a Set.

```python
fs = frozenset({1,2,3})
```

Elements cannot be added or removed.

---

## 24. Difference between Set and Frozen Set

| Set | Frozen Set |
|------|------------|
| Mutable | Immutable |
| Hashable ❌ | Hashable ✅ |
| Can modify | Cannot modify |

---

## 25. Why use Sets instead of Lists?

Because searching in Sets is much faster.

Average lookup:

**O(1)**

List lookup:

**O(n)**

---

# 🔴 Advanced Questions

## 26. How are Sets implemented?

Python Sets use a **Hash Table** internally.

---

## 27. What is Hashing?

Hashing converts an object into an integer hash value for quick lookup.

---

## 28. What is a Hash Table?

A data structure that stores key-value information using hash values.

Python Sets use Hash Tables.

---

## 29. Why must Set elements be immutable?

Mutable objects change their hash value, which breaks hash table lookup.

---

## 30. Can Lists be stored inside a Set?

No.

Lists are mutable.

```python
{[1,2]}
```

Raises

```
TypeError
```

---

## 31. Can Tuples be stored inside a Set?

Yes.

```python
{(1,2),(3,4)}
```

---

## 32. Can Dictionaries be stored inside a Set?

No.

Dictionaries are mutable.

---

## 33. What is the average lookup complexity?

**O(1)**

---

## 34. Worst-case lookup complexity?

**O(n)**

Occurs during excessive hash collisions.

---

## 35. Why are Sets unordered?

Because they are based on hash tables rather than indexes.

---

# ⚡ Time Complexity

| Operation | Complexity |
|------------|------------|
| add() | O(1) |
| remove() | O(1) |
| discard() | O(1) |
| pop() | O(1) |
| in | O(1) |
| union() | O(len(A)+len(B)) |
| intersection() | O(min(len(A),len(B))) |
| difference() | O(len(A)) |
| clear() | O(n) |

---

# 💻 Coding Interview Questions

1. Remove duplicates from a list.
2. Find union of two sets.
3. Find intersection of two sets.
4. Find difference of two sets.
5. Find symmetric difference.
6. Check subset.
7. Check superset.
8. Find common elements in two arrays.
9. Count distinct elements.
10. Find first repeating element.
11. Find first non-repeating element.
12. Remove duplicate characters from a string.
13. Count unique words.
14. Find pair with given sum.
15. Longest consecutive sequence.

---

# 🚀 Quick Revision

✅ Sets store unique values.

✅ Sets are unordered.

✅ Sets are mutable.

✅ Elements must be immutable.

✅ Lookup is O(1) on average.

✅ Uses Hash Tables internally.

✅ Supports mathematical operations like Union and Intersection.

✅ No indexing or slicing.

---

## ⭐ Interview Tips

- Know every built-in method.
- Learn all set operators (`|`, `&`, `-`, `^`).
- Remember the time complexities.
- Understand hashing and hash tables.
- Practice coding problems involving duplicates, unique elements, and fast lookups.

---

<div align="center">

### 🎯 Master Python Sets and Ace Your Interviews!

⭐ Happy Coding! 🐍

</div>

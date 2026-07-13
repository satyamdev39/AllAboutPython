# Python Functions - Programs Collection

This document contains common Python function programs with explanations and outputs.

---

# 1. Simple Function

```python
def greet():
    print("Hello, World!")

greet()
```

**Output**

```
Hello, World!
```

---

# 2. Function with Parameters

```python
def greet(name):
    print("Hello,", name)

greet("Alice")
```

**Output**

```
Hello, Alice
```

---

# 3. Function with Return Value

```python
def add(a, b):
    return a + b

result = add(10, 20)
print(result)
```

**Output**

```
30
```

---

# 4. Even or Odd

```python
def even_odd(num):
    if num % 2 == 0:
        return "Even"
    return "Odd"

print(even_odd(15))
```

**Output**

```
Odd
```

---

# 5. Square of a Number

```python
def square(num):
    return num ** 2

print(square(5))
```

**Output**

```
25
```

---

# 6. Cube of a Number

```python
def cube(num):
    return num ** 3

print(cube(3))
```

**Output**

```
27
```

---

# 7. Largest of Three Numbers

```python
def largest(a, b, c):
    return max(a, b, c)

print(largest(10, 50, 30))
```

**Output**

```
50
```

---

# 8. Smallest Number

```python
def smallest(a, b, c):
    return min(a, b, c)

print(smallest(10, 50, 30))
```

**Output**

```
10
```

---

# 9. Factorial (Recursion)

```python
def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n - 1)

print(factorial(5))
```

**Output**

```
120
```

---

# 10. Fibonacci Series

```python
def fibonacci(n):
    a, b = 0, 1

    for _ in range(n):
        print(a, end=" ")
        a, b = b, a + b

fibonacci(10)
```

**Output**

```
0 1 1 2 3 5 8 13 21 34
```

---

# 11. Prime Number

```python
def is_prime(n):
    if n < 2:
        return False

    for i in range(2, int(n**0.5) + 1):
        if n % i == 0:
            return False

    return True

print(is_prime(17))
```

**Output**

```
True
```

---

# 12. Palindrome

```python
def palindrome(text):
    return text == text[::-1]

print(palindrome("madam"))
```

**Output**

```
True
```

---

# 13. Reverse String

```python
def reverse(text):
    return text[::-1]

print(reverse("Python"))
```

**Output**

```
nohtyP
```

---

# 14. Count Vowels

```python
def count_vowels(text):
    count = 0

    for ch in text.lower():
        if ch in "aeiou":
            count += 1

    return count

print(count_vowels("Programming"))
```

**Output**

```
3
```

---

# 15. Sum of List

```python
def list_sum(numbers):
    return sum(numbers)

print(list_sum([10, 20, 30, 40]))
```

**Output**

```
100
```

---

# 16. Maximum in List

```python
def maximum(numbers):
    return max(numbers)

print(maximum([12, 45, 8, 100, 25]))
```

**Output**

```
100
```

---

# 17. Minimum in List

```python
def minimum(numbers):
    return min(numbers)

print(minimum([12, 45, 8, 100, 25]))
```

**Output**

```
8
```

---

# 18. Average of Numbers

```python
def average(numbers):
    return sum(numbers) / len(numbers)

print(average([10, 20, 30, 40]))
```

**Output**

```
25.0
```

---

# 19. Lambda Function

```python
square = lambda x: x * x

print(square(8))
```

**Output**

```
64
```

---

# 20. Function Using *args

```python
def total(*numbers):
    return sum(numbers)

print(total(10, 20, 30, 40, 50))
```

**Output**

```
150
```

---

# 21. Function Using **kwargs

```python
def student(**info):
    for key, value in info.items():
        print(key, ":", value)

student(name="John", age=20, city="Delhi")
```

**Output**

```
name : John
age : 20
city : Delhi
```

---

# 22. Default Argument

```python
def greet(name="Guest"):
    print("Hello", name)

greet()
greet("Alice")
```

**Output**

```
Hello Guest
Hello Alice
```

---

# 23. Nested Function

```python
def outer():

    def inner():
        print("Inside Inner Function")

    inner()

outer()
```

**Output**

```
Inside Inner Function
```

---

# 24. Generator Function

```python
def numbers():
    for i in range(1, 6):
        yield i

for value in numbers():
    print(value)
```

**Output**

```
1
2
3
4
5
```

---

# 25. Calculator Using Functions

```python
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    return a / b

print("Addition:", add(10, 5))
print("Subtraction:", subtract(10, 5))
print("Multiplication:", multiply(10, 5))
print("Division:", divide(10, 5))
```

**Output**

```
Addition: 15
Subtraction: 5
Multiplication: 50
Division: 2.0
```

---

# Practice Programs

1. Find the area of a circle using a function.
2. Find the perimeter of a rectangle.
3. Check Armstrong number using a function.
4. Check whether a year is a leap year.
5. Find the GCD of two numbers.
6. Find the LCM of two numbers.
7. Sort a list using a function.
8. Count words in a sentence.
9. Check whether a string is an anagram.
10. Create a simple menu-driven calculator using functions.

---

# Summary

This file includes:

- Simple Functions
- Parameterized Functions
- Return Functions
- Default Arguments
- *args
- **kwargs
- Lambda Functions
- Recursive Functions
- Generator Functions
- Nested Functions
- Calculator Program
- Number Programs
- String Programs
- List Programs
- Practice Programs

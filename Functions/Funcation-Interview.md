# Python Functions - Interview Questions and Answers

This document contains commonly asked Python function interview questions with answers and examples.

---

# 1. What is a function in Python?

**Answer:**

A function is a reusable block of code that performs a specific task. It helps reduce code duplication and improves readability.

Example:

```python
def greet():
    print("Hello")

greet()
```

---

# 2. Why do we use functions?

**Answer:**

- Code reusability
- Reduces duplication
- Easier debugging
- Better readability
- Modular programming
- Easy maintenance

---

# 3. What is the syntax of a function?

```python
def function_name(parameters):
    # code
    return value
```

---

# 4. What is the difference between a parameter and an argument?

| Parameter | Argument |
|-----------|----------|
| Variable in function definition | Actual value passed to function |

Example:

```python
def add(a, b):   # a and b are parameters
    return a + b

add(10, 20)      # 10 and 20 are arguments
```

---

# 5. What are the different types of arguments?

- Positional Arguments
- Keyword Arguments
- Default Arguments
- Variable-Length Arguments (*args)
- Keyword Variable-Length Arguments (**kwargs)

---

# 6. What is the difference between `return` and `print()`?

| return | print() |
|---------|----------|
| Returns a value | Displays output |
| Can be stored in a variable | Cannot be stored directly |
| Ends function execution | Function continues after printing |

Example:

```python
def add(a, b):
    return a + b

result = add(5, 3)
print(result)
```

---

# 7. What happens if a function has no `return` statement?

It returns **None** by default.

```python
def hello():
    print("Hi")

print(hello())
```

Output:

```
Hi
None
```

---

# 8. What are built-in functions?

Functions already provided by Python.

Examples:

```python
print()
len()
sum()
max()
min()
type()
range()
sorted()
```

---

# 9. What are user-defined functions?

Functions created by the programmer.

```python
def multiply(a, b):
    return a * b
```

---

# 10. What is a lambda function?

A lambda function is an anonymous (unnamed) function written in a single line.

```python
square = lambda x: x * x

print(square(5))
```

---

# 11. What is recursion?

A recursive function calls itself.

```python
def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n - 1)
```

---

# 12. What is a generator function?

A generator uses the `yield` keyword to return values one at a time.

```python
def numbers():
    yield 1
    yield 2
    yield 3
```

---

# 13. What is the difference between `yield` and `return`?

| return | yield |
|---------|--------|
| Returns one value | Returns values one at a time |
| Function ends | Function pauses and resumes |
| Used in normal functions | Used in generators |

---

# 14. What is `*args`?

`*args` allows a function to accept any number of positional arguments.

```python
def total(*numbers):
    return sum(numbers)

print(total(1, 2, 3, 4))
```

---

# 15. What is `**kwargs`?

`**kwargs` allows a function to accept any number of keyword arguments.

```python
def details(**info):
    print(info)

details(name="John", age=20)
```

---

# 16. What is the difference between `*args` and `**kwargs`?

| *args | **kwargs |
|--------|-----------|
| Positional arguments | Keyword arguments |
| Stored as tuple | Stored as dictionary |

---

# 17. What are default arguments?

Arguments with predefined values.

```python
def greet(name="Guest"):
    print(name)

greet()
```

---

# 18. What are keyword arguments?

Arguments passed using parameter names.

```python
def student(name, age):
    print(name, age)

student(age=20, name="Alice")
```

---

# 19. What is function scope?

Scope determines where a variable can be accessed.

Types:

- Local
- Global
- Enclosing
- Built-in (LEGB Rule)

---

# 20. What is the `global` keyword?

It allows modification of a global variable inside a function.

```python
count = 0

def increase():
    global count
    count += 1
```

---

# 21. What is the `nonlocal` keyword?

It allows modification of variables in the nearest enclosing function.

```python
def outer():
    x = 5

    def inner():
        nonlocal x
        x += 1
```

---

# 22. What is a nested function?

A function defined inside another function.

```python
def outer():
    def inner():
        print("Hello")

    inner()
```

---

# 23. What is a closure?

A closure remembers values from its enclosing scope even after the outer function has finished.

```python
def outer(msg):
    def inner():
        print(msg)
    return inner
```

---

# 24. What is a decorator?

A decorator modifies the behavior of another function.

```python
def decorator(func):
    def wrapper():
        print("Before")
        func()
        print("After")
    return wrapper
```

---

# 25. What is a docstring?

A docstring describes what a function does.

```python
def add(a, b):
    """Returns the sum of two numbers."""
    return a + b
```

---

# 26. What are function annotations?

Annotations provide type hints.

```python
def add(a: int, b: int) -> int:
    return a + b
```

---

# 27. Can a function return multiple values?

Yes.

```python
def calc(a, b):
    return a + b, a - b

x, y = calc(10, 5)
```

---

# 28. Can functions be passed as arguments?

Yes.

```python
def greet(name):
    return "Hello " + name

def display(func):
    print(func("Alice"))

display(greet)
```

---

# 29. Can a function call another function?

Yes.

```python
def add():
    return 5 + 3

def show():
    print(add())

show()
```

---

# 30. What are higher-order functions?

Functions that accept other functions as arguments or return functions.

Examples:

- `map()`
- `filter()`
- `reduce()`

---

# Frequently Asked Coding Questions

1. Write a function to check if a number is prime.
2. Write a function to calculate factorial.
3. Reverse a string using a function.
4. Find the largest element in a list.
5. Count vowels in a string.
6. Check if a string is a palindrome.
7. Write a recursive Fibonacci function.
8. Create a calculator using functions.
9. Use `*args` to sum numbers.
10. Use `**kwargs` to display employee details.

---

# Quick Revision

- Function
- Parameters
- Arguments
- Return
- print()
- Lambda
- Recursion
- Generator
- Decorator
- Closure
- Nested Function
- *args
- **kwargs
- Global
- Nonlocal
- Docstring
- Annotations
- Higher-Order Function
- Built-in Functions
- User-defined Functions

---

# Interview Tip

Always explain:
1. **What it is**
2. **Why it is used**
3. **Syntax**
4. **Example**
5. **Output**

This structure makes your answers clear and easy to follow during interviews.

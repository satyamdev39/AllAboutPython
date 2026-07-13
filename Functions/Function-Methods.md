# Python Function Methods (Complete Notes)

# Table of Contents

1. What is a Function?
2. Types of Functions
3. Function Argument Methods
4. Common Built-in Functions
5. Summary

---

# 1. What is a Function?

A **function** is a reusable block of code that performs a specific task.

Example:

```python
def greet():
    print("Hello, World!")

greet()
```

Output:

```
Hello, World!
```

---

# 2. Types of Functions

## 2.1 Built-in Functions

Functions that come with Python.

Example:

```python
print("Hello")
len("Python")
max(10, 20, 30)
min(5, 2, 8)
sum([1, 2, 3])
type(100)
abs(-10)
round(3.14159, 2)
```

---

## 2.2 User-defined Functions

Functions created by the programmer.

```python
def welcome():
    print("Welcome to Python!")

welcome()
```

---

## 2.3 Function Without Parameters

```python
def hello():
    print("Hello!")

hello()
```

---

## 2.4 Function With Parameters

```python
def add(a, b):
    print(a + b)

add(10, 20)
```

Output

```
30
```

---

## 2.5 Function With Return Value

```python
def square(x):
    return x * x

print(square(5))
```

Output

```
25
```

---

## 2.6 Function With Parameters and Return Value

```python
def multiply(a, b):
    return a * b

result = multiply(4, 5)
print(result)
```

Output

```
20
```

---

## 2.7 Lambda (Anonymous) Function

```python
square = lambda x: x * x

print(square(6))
```

Output

```
36
```

---

## 2.8 Recursive Function

A function that calls itself.

```python
def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n - 1)

print(factorial(5))
```

Output

```
120
```

---

## 2.9 Generator Function

Uses the `yield` keyword.

```python
def numbers():
    yield 1
    yield 2
    yield 3

for num in numbers():
    print(num)
```

Output

```
1
2
3
```

---

## 2.10 Nested Function

```python
def outer():
    def inner():
        print("Inside Inner Function")

    inner()

outer()
```

---

# 3. Function Argument Methods

## 3.1 Positional Arguments

```python
def student(name, age):
    print(name, age)

student("Alice", 20)
```

---

## 3.2 Keyword Arguments

```python
student(age=20, name="Alice")
```

---

## 3.3 Default Arguments

```python
def greet(name="Guest"):
    print("Hello", name)

greet()
greet("John")
```

Output

```
Hello Guest
Hello John
```

---

## 3.4 Variable-Length Arguments (*args)

```python
def total(*numbers):
    print(sum(numbers))

total(10, 20, 30, 40)
```

Output

```
100
```

---

## 3.5 Keyword Variable-Length Arguments (**kwargs)

```python
def details(**info):
    print(info)

details(name="John", age=25, city="Delhi")
```

Output

```
{'name': 'John', 'age': 25, 'city': 'Delhi'}
```

---

# 4. Common Built-in Functions

| Function | Description | Example |
|----------|-------------|---------|
| print() | Displays output | `print("Hello")` |
| input() | Reads user input | `input("Name: ")` |
| len() | Returns length | `len("Python")` |
| type() | Returns data type | `type(100)` |
| max() | Largest value | `max(1,5,3)` |
| min() | Smallest value | `min(1,5,3)` |
| sum() | Sum of numbers | `sum([1,2,3])` |
| abs() | Absolute value | `abs(-10)` |
| round() | Rounds a number | `round(3.145,2)` |
| sorted() | Sorts iterable | `sorted([4,2,1])` |
| range() | Generates sequence | `range(5)` |
| enumerate() | Adds index | `enumerate(["a","b"])` |
| zip() | Combines iterables | `zip(a,b)` |
| map() | Applies a function | `map(str, nums)` |
| filter() | Filters data | `filter(is_even, nums)` |
| any() | True if any element is True | `any([0,1,0])` |
| all() | True if all elements are True | `all([1,2,3])` |

---

# 5. Summary

## Types of Functions

- Built-in Functions
- User-defined Functions
- Functions Without Parameters
- Functions With Parameters
- Functions With Return Values
- Lambda Functions
- Recursive Functions
- Generator Functions
- Nested Functions

## Function Argument Methods

- Positional Arguments
- Keyword Arguments
- Default Arguments
- *args
- **kwargs

## Frequently Used Built-in Functions

- print()
- input()
- len()
- type()
- max()
- min()
- sum()
- abs()
- round()
- sorted()
- range()
- enumerate()
- zip()
- map()
- filter()
- any()
- all()

---

# Practice Questions

1. Create a function to calculate the area of a rectangle.
2. Write a function to find the largest of three numbers.
3. Create a recursive function to calculate factorial.
4. Write a lambda function to cube a number.
5. Use `*args` to add multiple numbers.
6. Use `**kwargs` to print employee details.
7. Write a generator that yields the first 10 natural numbers.
8. Explain the difference between positional and keyword arguments.
9. Demonstrate a nested function.
10. List five commonly used built-in functions.

---

**End of Notes**

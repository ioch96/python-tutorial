# Python Basics

## Variables in Python

A variable is used to store data in memory. In Python, you create a variable by assigning a value to a name using the `=` operator.

```python
x = 5
y = "Ioannis"
```

- x stores an integer value `5`
- y stores a string value `"Ioannis"`

You can display the value of a variable using the `print()` function:

```python
print(x)
print(y)
```

## Dynamic Typing

Python is a dynamically typed language. This means you do not need to declare the type of a variable explicitly, and the type can change during program execution.

```python
x = 4          # x is an integer
x = "Ioannis"  # x is now a string
print(x)
```

Here, the same variable `x` is first an integer and later reassigned to a string. Python automatically handles the type change.

## Type Casting (Type Conversion)

Python allows you to convert between different data types using built-in functions:

- `str()` &rarr; converts to string
- `int()` &rarr; converts to integer
- `float()` &rarr; converts to floating-point number

```python
x = str(3)
y = int(3)
z = float(3)

print(x)
print(y)
print(z)
```

Results:

- `x` becomes `'3'` (string)
- `y` becomes `3` (integer)
- `z` becomes `3.0` (float)

## Checking Variable Types

You can check the data type of a variable using the `type()` function:

```python
x = 5
y = "Ioannis"

print(type(x))
print(type(y))
```

Output:

- `<class 'int'>` for integers
- `<class 'str'>` for strings

This is useful for debugging and understanding how data is handled in your program.

## Strings and Quotation Marks

In Python, strings can be created using single quotes or double quotes. Both are treated the same.

```python
x = "Ioannis"
print(x)

x = 'Ioannis'
print(x)
```

Use whichever style you prefer, but be consistent for readability.

## Case Sensitivity in Python

Python is **case-sensitive**, meaning uppercase and lowercase letters are treated as different identifiers.

```python
a = 4
A = "Ioannis"

print(a)
print(A)
```

- `a` and `A` are two completely different variables
- This applies to variable names, function names, and keywords

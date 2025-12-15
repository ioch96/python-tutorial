# Python Variable Naming Conventions

This document explains **legal and illegal variable names** in Python, as well as common **naming styles** used when writing Python code. Understanding these rules and conventions helps you write readable and error-free programs.

---

## 1. Legal Variable Names

Python variable names:

- Must start with a **letter (a–z, A–Z)** or an **underscore (_)**
- Can contain letters, numbers, and underscores
- Are **case-sensitive**

Examples of valid variable names:

```python
myvar = "Ioannis"
my_var = "Ioannis"
_my_var = "Ioannis"
myVar = "Ioannis"
MYVAR = "Ioannis"
myvar2 = "Ioannis"
```

All of these variables are valid and can be printed:

```python
print(myvar)
print(my_var)
print(_my_var)
print(myVar)
print(MYVAR)
print(myvar2)
```

Each variable name is treated as a **different identifier** by Python.

---

## 2. Illegal Variable Names

Some variable names are **not allowed** in Python because they break naming rules.

```python
# 2myvar = "Ioannis"   # Cannot start with a number
# my-var = "Ioannis"   # Hyphens are not allowed
# my var = "Ioannis"   # Spaces are not allowed
```

Trying to use any of these will result in a **syntax error**.

---

## 3. Naming Styles (Conventions)

Python supports different naming styles. These are not rules, but **best practices**.

### Camel Case

Each word starts with a capital letter except the first one.

```python
myVariableName = "Ioannis"
```

Commonly used in other languages like JavaScript or Java.

---

### Pascal Case

Each word starts with a capital letter.

```python
MyVariableName = "Ioannis"
```

Often used for **class names** in Python.

---

### Snake Case (Recommended)

Words are separated by underscores and written in lowercase.

```python
my_variable_name = "Ioannis"
```

This is the **preferred naming convention in Python** according to PEP 8 (Python’s style guide).
Using clear and consistent variable names makes your code easier to read, understand, and maintain.

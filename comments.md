# Python Comments

This document explains how **comments** work in Python and how they are used to make code easier to understand and maintain.

---

## 1. Single-Line Comments

In Python, single-line comments start with the `#` symbol. Anything written after `#` on the same line is ignored by the Python interpreter.

```python
# This is a comment
print("Hello, World!")
```

Comments are commonly used to:

* Explain what the code does
* Add notes for yourself or other developers
* Temporarily disable code

---

## 2. Inline Comments

Comments can also be written at the **end of a line of code**. These are called inline comments.

```python
print("Hello, World!")  # This is a comment
```

Inline comments should be short and clearly describe the code on that line.

---

## 3. Multi-Line Comments (Docstrings)

Python does not have a special syntax for traditional multi-line comments. However, triple quotes (`"""`) are often used to write **multi-line strings**, which are commonly used as **docstrings**.

```python
"""
This is a comment
written in
more than just one line
"""

print("Hello, World!")
```

### Important Note

* Triple-quoted strings are **not true comments**
* They are string literals that Python ignores if they are not assigned to a variable
* They are mainly used for **documentation**, especially in functions, classes, and modules

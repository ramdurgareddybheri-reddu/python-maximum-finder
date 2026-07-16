
# Python Maximum Finder

This repository contains a simple Python program that demonstrates how to find the maximum number in a list without using built-in functions like `max()`.  
It’s a beginner-friendly example to understand loops, conditionals, and basic algorithm design.

---

## 🚀 Features
- Defines a list of numbers.
- Iterates through the list using a `for` loop.
- Compares each number to track the maximum value.
- Prints the largest number at the end.

---

## 📜 Code Example
```python
numbers = [1, 5, 2, 6, 7, 10]
maximum = numbers[0]

for number in numbers:
    if number > maximum:
        maximum = number

print(maximum)

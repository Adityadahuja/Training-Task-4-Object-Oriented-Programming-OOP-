# 🐍 Day 4 – Object-Oriented Programming (OOP) in Python

A comprehensive learning notebook covering all four pillars of OOP in Python — with theory, hands-on coding subtasks, real-world practice programs, and interview Q&A.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Topics Covered](#topics-covered)
- [Coding Subtasks](#coding-subtasks)
- [Practice Programs](#practice-programs)
- [Interview Q&A](#interview-qa)
- [Key Concepts at a Glance](#key-concepts-at-a-glance)
- [Prerequisites](#prerequisites)
- [How to Run](#how-to-run)

---

## Overview

This notebook is **Day 4** of a Python learning series. It introduces Object-Oriented Programming (OOP) — one of the most important paradigms in software development. The notebook covers all major OOP concepts with clear examples, practical programs, and interview preparation material.

---

## Topics Covered

| # | Topic |
|---|-------|
| 1 | Classes and Objects |
| 2 | Constructors (`__init__`) |
| 3 | Instance Variables and Methods |
| 4 | Class Variables |
| 5 | Encapsulation |
| 6 | Inheritance (Single, Multiple, Multilevel, Hierarchical) |
| 7 | Polymorphism |
| 8 | Abstraction (`abc` module) |
| 9 | Method Overriding |
| 10 | `super()` Function |
| 11 | Access Modifiers (Public, Protected, Private) |

---

## Coding Subtasks

Focused exercises that reinforce each concept one at a time:

| # | Task | Concept |
|---|------|---------|
| 1 | Create a `Student` class and object | Classes & Objects |
| 2 | Use `__init__` to set name and roll number | Constructors |
| 3 | Define attributes and a `display()` method | Instance Variables & Methods |
| 4 | `Manager` inheriting from `Employee` | Inheritance |
| 5 | `Car` and `Bike` with `start()` method | Polymorphism |
| 6 | `BankAccount` with private balance + deposit | Encapsulation |
| 7 | Abstract `Shape` class with `Rectangle` implementation | Abstraction |
| 8 | `Dog` overriding `Animal.sound()` | Method Overriding |
| 9 | Class vs instance variable demonstration | Class Variables |

---

## Practice Programs

Six applied programs covering real-world scenarios:

| # | Program | OOP Concepts Used |
|---|---------|-------------------|
| 1 | **Student Management System** | Classes, methods, grade calculator |
| 2 | **Bank Account System** | Encapsulation, deposit/withdraw logic |
| 3 | **Employee Management System** | Inheritance |
| 4 | **Vehicle System** | Polymorphism, method overriding |
| 5 | **Shape Area Calculator** | Abstraction, `abc` module |
| 6 | **Library Management System** | Multi-class design (Book, Member, Library) |

---

## Interview Q&A

The notebook includes answers to 10 common OOP interview questions:

1. What is a class?
2. What is an object?
3. Difference between class and object?
4. What is inheritance?
5. What is polymorphism?
6. What is encapsulation?
7. What is abstraction?
8. Difference between method overriding and overloading?
9. What is the purpose of `super()`?
10. What are public, protected, and private members?

---

## Key Concepts at a Glance

```python
# Class & Constructor
class Student:
    school_name = "ABC School"          # class variable

    def __init__(self, name, marks):
        self.name = name                # instance variable
        self.marks = marks

# Inheritance + super()
class Manager(Employee):
    def __init__(self, name):
        super().__init__(name)

# Encapsulation
class BankAccount:
    def __init__(self, balance):
        self.__balance = balance        # private

    def get_balance(self):
        return self.__balance

# Polymorphism
class Car(Vehicle):
    def start(self):
        print("Car starts with key")

# Abstraction
from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def area(self):
        pass
```

---

## Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab
- Completion of Day 3 (Functions & Code Reusability) recommended

---

## How to Run

```bash
jupyter notebook "Day_4_Assignment___Object-Oriented_Programming__OOP_.ipynb"
```

Or open in [Google Colab](https://colab.research.google.com/) by uploading the `.ipynb` file.

---

## Author

**Aditya** — Python Learning Series, Day 4

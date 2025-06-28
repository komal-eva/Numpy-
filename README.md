# 📊 NumPy Basics — Quick Reference for Beginners

Welcome to my NumPy practice notebook! This repo contains all the important NumPy functions and examples I used to understand and revise the core concepts of numerical computing in Python.

---

## 🔹 What is NumPy?

**NumPy** (Numerical Python) is a Python library used for:
- Fast mathematical operations on arrays
- Multidimensional data structures
- Linear algebra, statistics, and random number generation

It's the foundation of most Python-based data science and machine learning libraries.

---

## 🧪 Key Features Covered

- ✅ Creating arrays (`array`, `zeros`, `ones`, `full`, `eye`)
- ✅ Array properties: `shape`, `ndim`, `size`, `dtype`
- ✅ Indexing and slicing arrays
- ✅ Array reshaping and flattening
- ✅ Mathematical operations: `add`, `subtract`, `multiply`, `dot`
- ✅ Statistical functions: `sum`, `mean`, `max`, `min`, `std`
- ✅ Random number generation with `np.random`
- ✅ Sorting, unique values, linspace, arange

---

## 🧾 Example Code Snippet

```python
import numpy as np

a = np.array([[1, 2], [3, 4]])
b = np.ones((2, 2))

result = np.dot(a, b)
print("Dot Product:\n", result)


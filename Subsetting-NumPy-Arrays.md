# Reflection: Subsetting NumPy Arrays

## 📘 Exercise
**Topic:** Subsetting NumPy Arrays  
Subsetting (using the square bracket notation on lists or arrays) works exactly the same with both lists and arrays.

This exercise already has two lists, `height_in` and `weight_lb`, loaded in the background.  
These contain the height and weight of MLB players as regular Python lists.  
It also has two NumPy arrays, `np_weight_lb` and `np_height_in`, prepared for you.

---

## 🧩 Instructions
- Subset `np_weight_lb` by printing out the element at index **50**.  
- Print out a sub-array of `np_height_in` that contains the elements from index **100** up to and including **index 110**.

---

## 💻 Script
```python
import numpy as np

np_weight_lb = np.array(weight_lb)
np_height_in = np.array(height_in)

# Print out the weight at index 50
print(np_weight_lb[50])

# Print out sub-array of np_height_in: index 100 up to and including index 110
print(np_height_in[100:111])

---

## Result

200
[73 74 72 73 69 72 73 75 75 73 72]

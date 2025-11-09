# Python Notes – 2D NumPy Arrays

## 🧩 Concept
When working with data that has multiple related values (like height and weight), it’s more efficient to represent it in a **2D array** instead of separate 1D lists.  
In a 2D array:
- Each **row** represents one data record (e.g., one baseball player).
- Each **column** represents a variable (e.g., height, weight).

NumPy makes it easy to store and manipulate such data.

---

## 💻 Example Code
```python
import numpy as np

# Create a 2D numpy array from a list of lists
np_baseball = np.array(baseball)

# Print out the shape of np_baseball
print(np_baseball.shape)
```

## Result
(1015, 2)

# Reflection: Creating and Converting a NumPy Array

## 🧩 Instructions
Create a NumPy array from `height_in`. Name this new array `np_height_in`.  
Print `np_height_in`.  
Multiply `np_height_in` by `0.0254` to convert all height measurements from inches to meters.  
Store the new values in a new array, `np_height_m`.  
Print out `np_height_m` and check if the output makes sense.

---

## 🧮 Script
```python
# Import numpy
import numpy as np

# Create a numpy array from height_in: np_height_in
np_height_in = np.array(height_in)

# Print out np_height_in
print(np_height_in)

# Convert np_height_in to m: np_height_m
np_height_m = np_height_in * 0.0254

# Print np_height_m
print(np_height_m)


---


## Result
```python
[74 74 72 ... 75 75 73]
[1.8796 1.8796 1.8288 ... 1.905  1.905  1.8542]

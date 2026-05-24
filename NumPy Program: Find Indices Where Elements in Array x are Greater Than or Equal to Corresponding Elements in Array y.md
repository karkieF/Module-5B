# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np

x = np.array([1, 5, 7, 8, 3])
y = np.array([2, 5, 6, 4, 3])

indices = np.where(x >= y)

print("Indices where x >= y:", indices)
```
## Output
<img width="391" height="35" alt="image" src="https://github.com/user-attachments/assets/b0f2d98b-1c0a-400d-8f0b-5bfb3430b6c4" />

## Result
Thus, the NumPy program to find indices where elements in array x are greater than or equal to array y was executed successfully.

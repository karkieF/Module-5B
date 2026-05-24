# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np

arr = np.array([[9, 2, 7],
                [4, 8, 1],
                [6, 3, 5]])

sorted_arr = np.sort(arr, axis=0)

print("Original Array:")
print(arr)

print("Column-wise Sorted Array:")
print(sorted_arr)
```

## Output
<img width="240" height="226" alt="image" src="https://github.com/user-attachments/assets/d7962825-8bb2-4a5f-8b2a-5e0342310299" />

## Result
Thus, the NumPy program to sort a 2D array column-wise was executed successfully.

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
arr = np.array(eval(input()))
print("Given array")
print("",arr)
print()
sorted_arr = np.sort(arr, axis=0)
print(sorted_arr)

```
## Output
<img width="609" height="850" alt="529928617-bcd380f2-b5ba-4013-a477-176e57dc8dad" src="https://github.com/user-attachments/assets/f425ea7e-51a5-43ca-b581-af396c10c333" />

## Result
Thus,the given python program has been executed successfully.


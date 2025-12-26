# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
import numpy as np
lst=eval(input())
a=np.array(lst)
print("Printing Original array")
print(a)
lst1=eval(input())
new_col=np.array(lst1)
after_delete=np.delete(a,1,axis=1)
print("Array after deleting column 2 on axis 1")
print(after_delete)
final_array=np.insert(after_delete,1,new_col,axis=1)
print("Array after inserting column 2 on axis 1")
print(final_array)
```

## Output
<img width="716" height="775" alt="529917180-610cfdc5-c771-4b63-a02e-d39f6c67376e" src="https://github.com/user-attachments/assets/68f52fd4-ba21-4224-9744-0239183719a8" />

## Result
Thus,the given Python Program has been executed successfully.


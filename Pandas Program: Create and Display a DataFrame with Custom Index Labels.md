# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import pandas as pd
d=eval(input())
df=pd.DataFrame(d)
print(df)
s=pd.Series(eval(input()))
print(s.to_frame())
```
## Output
<img width="1235" height="866" alt="529934670-fb6f8912-6951-41b4-bfb0-e0e0aab477e2" src="https://github.com/user-attachments/assets/54eaa84c-74dd-4604-bc16-1c28a6d851c7" />

## Result
Thus,the given Python Program has been executed successfully.


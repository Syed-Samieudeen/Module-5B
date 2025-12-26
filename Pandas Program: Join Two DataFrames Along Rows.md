# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd
df1 = pd.DataFrame(eval(input()))
df2 = pd.DataFrame(eval(input()))
df3 = pd.DataFrame(eval(input()))
print("Original DataFrames:")
print(df1)
print(df2)
print(df3)
result_data = pd.concat([df1, df2], ignore_index=False)
print("\nJoin first two said dataframes along rows:")
print(result_data)
final_data = pd.merge(result_data, df3, on='s_id')
print("\nNow join the said result_data and df_exam_data along student_id:")
print(final_data)
```

## Output
<img width="845" height="885" alt="529919663-eb0f1aea-ecac-4947-8169-88b0cb1f2fdb" src="https://github.com/user-attachments/assets/399ee2b6-0113-4422-9b36-976814efd2b7" />

## Result
Thus,the given Python Program has been executed successfully.


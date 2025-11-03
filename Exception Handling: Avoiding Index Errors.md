# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
try:
    lst=[5, 10, 20]
    print(lst[5])
except IndexError:
    msg="You're out of list range"
    print(msg)
```
## Output
<img width="406" height="134" alt="Screenshot 2025-11-03 193547" src="https://github.com/user-attachments/assets/6aad31b6-487e-4487-8328-5f0c2960e63e" />

## Result
Thus,the program is executed successfully

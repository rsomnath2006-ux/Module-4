## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
def merge_dicts(dict1, dict2):
    return {**dict1, **dict2}
dict1 =eval(input())
dict2 =eval(input())
result = merge_dicts(dict1, dict2)
print(result)
```
## Output
<img width="1274" height="161" alt="Screenshot 2025-11-03 192543" src="https://github.com/user-attachments/assets/0c166e91-7cff-4a41-8b3a-b091f52bf50c" />

## Result
Thus,the program is executed successfully

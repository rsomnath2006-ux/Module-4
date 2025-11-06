# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
with open("story.txt", "w") as f:
    f.write("""This is a test
Another line
Test line
Hello world""")
count=0
with open("story.txt", "r") as f:
    for line in f:
        line=line.strip()
        if line and line[0]!='T':
            count+=1
print("Sum:", count)
```
## Output
<img width="1858" height="1092" alt="Screenshot 2025-11-06 133029" src="https://github.com/user-attachments/assets/e68a6960-76e9-4874-8d29-30f26cf46ba4" />

## Result
Thus,the program is executed successfully

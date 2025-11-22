# EX 4e: File Handling in Python: Count Lines Not Starting with 'T'

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
n = int(input())
a, b = 0, 1

for i in range(n):
    print(a)
    a, b = b, a + b
```


## Output
<img width="415" height="417" alt="Screenshot 2025-11-22 094053" src="https://github.com/user-attachments/assets/166e68cc-b52b-46e6-af89-0634be3c94fe" />

## Result
Thus, the program successfully generated the Fibonacci series for the given number of terms.

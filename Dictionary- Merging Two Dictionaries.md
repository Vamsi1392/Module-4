## EX 4b: Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
age = int(input())
print("Age is:")
print(age)

try:
    if age < 0:
        raise ValueError("Input Correct age.")
    else:
        year_of_birth = 2022 - age
        print("Year of Birth is:")
        print(year_of_birth)
except ValueError as e:
    print(e)
```

## Output
<img width="584" height="283" alt="Screenshot 2025-11-22 093546" src="https://github.com/user-attachments/assets/7d35e4e1-e7ef-4127-bb1d-14a8951e1b4d" />


## Result
Thus, the program successfully checks if the age is negative and raises an exception using the raise keyword.

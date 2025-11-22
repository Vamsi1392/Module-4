#EX 4c: Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()

def reverse_file_content(input_file_path, output_file_path):
    with open(input_file_path, 'r') as file:
        content = file.read()
    with open(output_file_path, 'w') as file:
        file.write(content[::-1])
```

## Sample Output
<img width="1136" height="335" alt="Screenshot 2025-11-22 093742" src="https://github.com/user-attachments/assets/1cabef6b-1274-4469-8040-38195112eab0" />


## Result
Thus, the Python program successfully reversed the contents of a file and saved the reversed text into another file.


# EX 4d: Exception Handling in Python: Avoiding Index Errors

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
class CSE:
    def setvalues(self, a, b):
        self.a = a
        self.b = b

    def mul(self):
        print("Result: ", self.a * self.b)

    def div(self):
        if self.b != 0:
            print("Result: ", self.a // self.b)
        else:
            print("Cannot divide by zero")

a = int(input())
b = int(input())

obj = CSE()
obj.setvalues(a, b)
while True:
    choice = int(input())
    if choice == 1:
        obj.mul()
    elif choice == 2:
        obj.div()
    elif choice == 0:
        print("Exiting!")
        break
    else:
        print("Invalid choice")
```

## Output
<img width="443" height="288" alt="Screenshot 2025-11-22 093916" src="https://github.com/user-attachments/assets/c8c0b9f4-c315-4294-92bb-69dfc433da3d" />


## Result
Thus, the Python program using a class and conditional statements successfully performed multiplication or floor division based on the user's choice.

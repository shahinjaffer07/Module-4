# Exception Handling in Python: Avoiding Index Errors
Reg:212223040190

Name: SHAHIN J
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
    L = []
    for i in range(3):
        item = ['laptop','mobile','pen']
        L.append(item)

    print(L[4])

except IndexError:
    print("check index range")
```
## Output
![image](https://github.com/user-attachments/assets/de94eba5-953a-4850-ab1f-c01cdf80a881)

## Result
Thus, the program has been successfully executed.

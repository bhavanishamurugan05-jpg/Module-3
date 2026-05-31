# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
s = "google"

rev = ""
for i in range(len(s) - 1, -1, -1):
    rev += s[i]

if s == rev:
    print("Palindrome")
else:
    print("Not a Palindrome")
```

## Output
<img width="587" height="238" alt="image" src="https://github.com/user-attachments/assets/512921ff-3538-4777-8579-91a10d4336c2" />

## Result
Thus, the Python program successfully checks whether the given string is a palindrome or not without using built-in palindrome checking functions.

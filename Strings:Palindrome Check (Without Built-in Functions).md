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

~~~
a=input()
b=input()
uniq=[]
for i in a:
    if i in b and i not in uniq:
        uniq.append(i)
if uniq:
    for i in uniq:
        print(i)
    print("are the common characters")
else:
    print("There are no common characters")
~~~
## Output
<img width="767" height="269" alt="image" src="https://github.com/user-attachments/assets/6f20f4ea-f3e6-4787-a237-a79203cfe763" />

## Result
Thus, the program has been successfully executed.

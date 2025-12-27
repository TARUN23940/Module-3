# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
~~~
import re
word = input()
pt = r'[a-z]+_[a-z]+'
if re.search(pt, word):
    print("Found a match!")
else:
    print("Not matched!")
~~~
## Output
<img width="597" height="186" alt="image" src="https://github.com/user-attachments/assets/f48fea4d-268a-4c3c-8d5b-4d76119dc256" />

## Result
Thus, the program has been successfully executed.

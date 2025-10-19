# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
numbers = [10, 20, 30, 40, 50]
total = sum(numbers)
print("Sum of the list items is:", total)
```

## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-19 160308" src="https://github.com/user-attachments/assets/0bf20f91-566a-40e0-ba5f-5effde590f42" />

## Result
Thus To write a Python program that calculates the **sum of all elements** in a list has been executed sucessfully.

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
```
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1 = []

for i in items:
    if not re.search(r'e', i):
        l1.append(i)

print("Filtered words without 'e':", l1)
```
## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-19 160551" src="https://github.com/user-attachments/assets/d6355b5f-5111-4f18-979a-2b58ef5c5ed5" />

## Result

Thus To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)** has been executed sucessfully.


# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(string):
    n = int(input("Enter the index to remove: "))
    a = ""
    for i in range(len(string)):
        if i != n:
            a += string[i]
    return a

input_string = input("Enter a string: ")
result = remove(input_string)
print("String after removal:", result)
```

## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-19 161011" src="https://github.com/user-attachments/assets/fc1382e2-3dc9-46ae-b344-4bb764b4d0b9" />

## Result

Thus To write a Python program that accepts a string and removes the character at a specified index has been executed sucessfully

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
string = "google"
reversed_string = string[::-1]

if string == reversed_string:
    print(f'"{string}" is a palindrome.')
else:
    print(f'"{string}" is not a palindrome.')
```
Add code here

## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-19 161223" src="https://github.com/user-attachments/assets/d9d7241d-08f0-4a9c-9606-fbee03007374" />

## Result
Thus To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions has been executed sucessfully.


# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
x = ('a', 'b', 'n', 4, 8, 9)

# Check if 'n' exists
exists_n = 'n' in x
# Check if 8 exists
exists_8 = 8 in x

print(f"'n' exists in tuple: {exists_n}")
print(f"8 exists in tuple: {exists_8}")
```

## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-19 161501" src="https://github.com/user-attachments/assets/afa6d513-e789-4f94-9e04-9cb010b7510a" />

## Result
Thus To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple has been executed sucessfully.

# Module-3
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
~~~
Function to remove nth index character

def remove(s): n = int(input("Enter index to remove: ")) a = ""

for i in range(len(s)):
    if i != n:
        a += s[i]

return a
nput string
string = input("Enter a string: ")

Function call
result = remove(string)

Print result
print("String after removing character:", result)
~~~
## Output

<img width="621" height="199" alt="image" src="https://github.com/user-attachments/assets/5505b96f-7ae2-4819-ac31-8652788429c" />

## Result
Thus, the Python program successfully removes the character at the specified index from the given string.

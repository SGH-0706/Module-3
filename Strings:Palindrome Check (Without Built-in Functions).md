# 3D Strings-Palindrome Check in Python (Without Built-in Functions)
## Developed by : Srinithi Muthukumar
## Register No. : 212224240161
## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program : 
```
def palindrome(a):
    mid=len(a)//2
    start=0
    last=len(a)-1
    flag=1
    while start<=mid:
        if a[start]!=a[last]:
            flag=0
            break
        start+=1
        last-=1
    if flag:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
string=input()
palindrome(string)
```
## Output :

<img width="1012" height="217" alt="image" src="https://github.com/user-attachments/assets/3b9d3eaa-7f65-41e8-afb6-e481d6dba0be" />

## Result :
Thus the Python program to check whether the given string is a palindrome or not is executed successfully.

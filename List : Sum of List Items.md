# 3A List Operations in Python: Sum of List Items
## Developed by : Srinithi Muthukumar
## Register No. : 212224240161
## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
def createlist(n):
    l=[]
    for i in range(1,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list = ",sum(l))
```
## Output

<img width="958" height="263" alt="image" src="https://github.com/user-attachments/assets/d55b4891-b86e-4fb2-94da-5c1e7e0460f3" />

## Result
Thus Python program to calculate the sum of all even elements in a list is executed successfully.

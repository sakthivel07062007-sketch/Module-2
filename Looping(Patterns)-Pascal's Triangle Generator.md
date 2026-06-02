# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
n=int(input())
for i in range(n):
for k in range(n,i+1,-1):
        print(" ",end='')
        
    num=1
    for j in range(i+1):
        print(num,end=" ")
        num=num*(i-j)//(j+1)
    print()
```
## Sample Output

<img width="378" height="398" alt="566177026-26e6dd55-7854-4c9b-b4ca-a189fbfc3d0e" src="https://github.com/user-attachments/assets/e0667b99-eb86-4b60-83c2-1334d3140d69" />

## Result
Thus the python program to generate Pascals's triangle has beem executed successfully.

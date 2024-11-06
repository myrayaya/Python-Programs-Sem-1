![image](https://github.com/user-attachments/assets/c0b21ace-c050-4052-8d2d-60247fca4e24)# Programming With Python Semester-1
## Program-1: Write a program to find the roots of a quadratic equation
---
## Code:

a = int(input("Enter the value: "))
b = int(input("Enter the value: "))
c = int(input("Enter the value: "))

d = b ** 2 - 4 * a * c

if d >= 0:
    r1 = (-b + (d) ** 0.5) / 2 * a
    r2 = (-b - (d) ** 0.5) / 2 * a
    
    print("The roots are real", r1, " and ", r2)
else:
    print("There are no real roots")
    
![image](https://github.com/user-attachments/assets/285a7ac6-a807-4f1d-8d24-0688b05b27d3)

![image](https://github.com/user-attachments/assets/80fb20aa-2e83-45cd-bea3-d946984abb55)

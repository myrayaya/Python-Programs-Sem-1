## Program-2: Write a program to accept a number 'n' to compute the following:
## a) Check if 'n' is prime or not
## b) Generate all prime numbers till 'n'
---

a) 
n = int(input('Enter the value: '))

if n>1:
    for i in range (2,n):
        
        if n % i== 0:
            print(n, "is not a Prime Number")
            break
        else:
            print(n, "is a Prime Number")
            break
        
    else:
        print (n, "is not a Prime Number")
![image](https://github.com/user-attachments/assets/cedbad50-57c7-443c-b453-6a56b6e0c83e)
![image](https://github.com/user-attachments/assets/ddcc6489-b790-4611-9964-d6e2bd68154a)

b) 
n= int(input("enter value: "))

for num in range(1,n):

    if num > 1:
    
        for i in range (2, num):
        
            if num % i == 0:
            
                break
                
            else:
            
                print(num, end = ",")

![image](https://github.com/user-attachments/assets/b7c9c52b-a287-44c3-8555-9dd97bf7fb56)

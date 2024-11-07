## Program 6:  Write a program to swap the first n characters of two strings.

## Code:

```
string1 = input("Enter the first string: ")
string2 = input("Enter the second string: ")
n1 = int(input("Enter the no. of character/s to be swapped: "))
m = string1[:n1]
n = string2[:n1]
if n1 <= min(len(string1),len(string2)):
    print ("String 1 after swapping: ", string1.replace(m,n))
else:
    print ("String 2 after swapping: ", string2.replace(n,m))

```
![image](https://github.com/user-attachments/assets/d63e3255-7da7-45aa-b083-a664475a160b)

![image](https://github.com/user-attachments/assets/52789869-3786-4ff8-a263-2e3c5899d530)

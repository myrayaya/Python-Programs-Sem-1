## Write a program that accepts a character and performs the following:
a) print whether the character is a letter or numeric digit or a special character
b) if the character is a letter, print whether the letter is uppercase or lowercase
c) if the character is a numeric digit, prints its name in text
---
## Code:

charac = input("Enter the data: ")
if charac >= 'A' and charac <= 'Z':
    print(charac, "is an Uppercase Letter")
elif charac >= 'a' and charac <= 'z':
    print(charac, "is a Lowercase Letter")
elif charac >= '0' and charac <= '9':
    print(charac, "is a Numeric Digit")
    n = int(charac)
    dict= {0 : 'zero', 1 : 'one', 2 : 'two', 3 : 'three', 4 : 'four', 5 : 'five', 6 : 'six', 7 : 'seven', 8 : 'eight', 9 : 'nine'}
    print(dict[n])
else:
    print(charac, "is a Special Character")

![image](https://github.com/user-attachments/assets/c14e532c-2d0f-46af-9c9f-decc88cdb9a4)
![image](https://github.com/user-attachments/assets/fb226976-f775-4278-aaa2-2d06893a66d8)
![image](https://github.com/user-attachments/assets/4d5ae7fc-1275-4ac3-8428-61a753fdf1ca)
![image](https://github.com/user-attachments/assets/59b64677-2153-40f0-9df5-91243939fcdc)

## Program 5: Write a program to perform the following operations on a string

a. Find the frequency of a character in a string. 

b. Replace a character by another character in a string.

c. Remove the first occurrence of a character from a string. 

d. Remove all occurrences of a character from a string.

## Code:

a) 

```
string = "hello, welcome to python"
charac = input("Enter a character: ")
f = 0
for i in string:
    if i == charac:
        f += 1
print ("Frequency of", charac, "is", f)
```

![image](https://github.com/user-attachments/assets/e5e79021-7f58-48f5-a506-3f8832a516da)

![image](https://github.com/user-attachments/assets/8401e695-a497-42c7-8e93-f938b78971b5)

b) 

```
string = "hello, welcome to python"
print ("The string is: ", string)
print ('\n', 'The string after replacement is: ', string.replace('h','t'))

```

![image](https://github.com/user-attachments/assets/2dd0c370-3950-4633-b756-631a4d9700a6)

c)

```
string = "hello, welcome to python"
print("The string is: ", string)
print ('\n', 'The string after removing first occurence is: ', string[1:len(string)])

```

![image](https://github.com/user-attachments/assets/6da69b96-69b3-42fb-b119-34ac9fd22688)

d)

```
string = "hello, welcome to python"
print("The string is: ", string)
print ('\n', 'The string after removing all occurences of a charcter is: ', string[:0])

```

![image](https://github.com/user-attachments/assets/3bedc991-f40f-41db-9d0d-b969fa7b74de)

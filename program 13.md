## Program 13: WAP to accept a name from a user. Raise and handle appropriate exception(s) if the text entered by the user contains digits and/or special character

## Code:

```
name = input("Enter a name: ")
try:
    if name.isalpha():
        print("This is correct Name")
    
    else:
        raise Exception("There is NameError")
except Exception as e:
    print(e)
```

![image](https://github.com/user-attachments/assets/67cdfd60-82cb-44cc-b8e7-32bfc59e11d9)

![image](https://github.com/user-attachments/assets/e4245c01-b590-4f37-a017-478858585e15)

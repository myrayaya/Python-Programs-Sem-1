## Program 7: Write a function that accepts two strings and returns the indices of all the occurrences of the second string in the first string as a list. If the second string is not present in the first string then it should return -1.

## Code:

```
def occur(m, n):
    indices = []
    index = m.find(n)
    
    while index != -1:
        indices.append(index)
        index = m.find(n, index + 1)
    
    return indices if indices else -1
    
m = input("Enter the first string: ")
n = input("Enter the second string: ")
results = occur(m, n)
print("The occurences are", results)

```
![image](https://github.com/user-attachments/assets/b09d5ee4-8882-4bd4-8d60-b41aebc4d6fa)

![image](https://github.com/user-attachments/assets/8054c392-5474-45e8-a661-96136de9adce)

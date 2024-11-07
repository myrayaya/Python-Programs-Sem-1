## Program 8: WAP to create a list of the cubes of only the even integers appearing in the input list (may have elements of other types also) using the following: 

### a) 'for' loop 

### b) list comprehension


## Code: 

```
def cube_even_int():
    cubes = []
    number = [1, 2, 3, 4, "five", 6, 7, "eight", 9, 10]
    
    for i in number:
        if type(i) == int:
            
            if i % 2 == 0:
                cubes.append(i ** 3)
        
    print(cubes)
cube_even_int()

```

![image](https://github.com/user-attachments/assets/fa119da6-d8f8-4cbb-a2d9-10c064920f2e)

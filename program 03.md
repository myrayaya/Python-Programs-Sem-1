## Program-3 Write a program to create a pyramid of the character ' * ' and reverse pyramid.
## Code:

```
def print_pyramid(n):
    for i in range(n):
        # Print spaces
        print(' ' * (n - i - 1), end='')
        # Print asterisks
        print('*' * (2 * i + 1))

# Number of rows for the pyramid
rows = 5
print("Pyramid:")
print_pyramid(rows)

```

![image](https://github.com/user-attachments/assets/edba8618-4e23-4b5c-b2c5-1e554e8e9a39)

```
def print_reverse_pyramid(n):
    for i in range(n, 0, -1):
        # Print spaces
        print(' ' * (n - i), end='')
        # Print asterisks
        print('*' * (2 * i - 1))

# Number of rows for the reverse pyramid
rows = 5
print("\nReverse Pyramid:")
print_reverse_pyramid(rows)

```

![image](https://github.com/user-attachments/assets/ff3a0649-c719-4ea9-81c9-be6420da1c8b)

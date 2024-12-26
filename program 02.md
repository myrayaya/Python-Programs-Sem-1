## Program-2: Write a program to accept a number 'n' to compute the following:
## a) Check if 'n' is prime or not
## b) Generate all prime numbers till 'n'

```
def prime(num):
    """Check if a number is prime."""
    if num <= 1:
        return False
    for i in range(2, int(num**0.5) + 1):
        if num % i == 0:
            return False
    return True

def prime_num_list(n):
    """Generate a list of all prime numbers up to n."""
    primes = []
    for num in range(2, n + 1):
        if prime(num):
            primes.append(num)
    return primes

n = int(input("enter the num: "))
prime_num = prime_num_list(n)
print(list(prime_num))
```

![image](https://github.com/user-attachments/assets/cedbad50-57c7-443c-b453-6a56b6e0c83e)

![image](https://github.com/user-attachments/assets/ddcc6489-b790-4611-9964-d6e2bd68154a)

![image](https://github.com/user-attachments/assets/b7c9c52b-a287-44c3-8555-9dd97bf7fb56)

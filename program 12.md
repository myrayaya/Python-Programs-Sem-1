## Program 12: Consider a tuple t1=(1, 2, 5, 7, 9, 2, 4, 6, 8, 10). Write a program to perform following operations: 

a. Print half the values of the tuple in one line and the other half in the next line.

b. Print another tuple whose values are even numbers in the given tuple. 

c. Concatenate a tuple t2=(11,13,15) with t1. 

d. Return maximum and minimum value from this tuple

---

## Code:

a)

```
t1 = (1, 2, 5, 7, 9, 2, 4, 6, 8, 10)
half = len(t1)//2
first = t1[:half]
print("The first half of the Tuple: ", first)
second = t1[half:]
print("The second half of the Tuple: ", second)
```

![image](https://github.com/user-attachments/assets/a9afd293-01b3-47ce-9810-a30cb025e786)

b) 

```
t1 = (1, 2, 5, 7, 9, 2, 4, 6, 8, 10)
even_no = tuple(filter(lambda x: x % 2 == 0, t1))
print("The tuple with even number: ", even_no)
```

![image](https://github.com/user-attachments/assets/02a7ac43-0dcb-4d01-81a0-23b299013146)

c) 

```
t1 = (1, 2, 5, 7, 9, 2, 4, 6, 8, 10)
t2 = (11, 13, 15)
print("Tuple 1: ", t1)
print("Tuple 2: ", t2)
concat = (t1 + t2)
print("The tuple after Concatenation: ", concat)
```

![image](https://github.com/user-attachments/assets/795d4cd3-77f2-43b4-9381-aa3d293d776c)

d) 

```
t1 = (1, 2, 5, 7, 9, 2, 4, 6, 8, 10, 11, 13, 15)
print("The maximum value of tuple: ", max(t1))
print("The minimum value of tuple: ", min(t1))
```

![image](https://github.com/user-attachments/assets/33300e8b-9c5d-43e7-9298-b6ccbe6337b7)

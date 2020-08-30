# Solving-python-programming-exercises
Repository for my solution on https://github.com/zhiwehu/Python-programming-exercises


Question 1: Write a program which will find all such numbers which are divisible by 7 but are not a multiple of 5, between 2000 and 3200 (both included). The numbers obtained should be printed in a comma-separated sequence on a single line
Solution:
``` python
for i in range(2000,3201):
	if not i%7 and i%5:
		print(i, end =",")
```

Question 2
Level 1

Question: Write a program which can compute the factorial of a given numbers. The results should be printed in a comma-separated sequence on a single line. Suppose the following input is supplied to the program: 8 Then, the output should be: 40320.
Solution:
``` python
def factorial(n):
	if n == 1:
		return 1
	return n * factorial(n-1)
factorial(8)
```

Question 3
Level 1

Question: With a given integral number n, write a program to generate a dictionary that contains (i, i*i) such that is an integral number between 1 and n (both included). and then the program should print the dictionary. Suppose the following input is supplied to the program: 8 Then, the output should be: {1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64}
Solution:
```python
def dictionary(n):
	temp = dict()
	for i in range(1, n+1):
		temp[i] = i*i
	return temp
```

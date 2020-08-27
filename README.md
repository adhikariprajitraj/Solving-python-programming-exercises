# Solving-python-programming-exercises
Repository for my solution on https://github.com/zhiwehu/Python-programming-exercises

Question: Write a program which will find all such numbers which are divisible by 7 but are not a multiple of 5, between 2000 and 3200 (both included). The numbers obtained should be printed in a comma-separated sequence on a single line
Solution:
``` python
for i in range(2000,3201):
	if not i%7 and i%5:
		print(i, end =",")
```

---
{"dg-publish":true,"permalink":"/ba/week-6-principles-of-programming/","title":"week 6 - Principles of programming","created":"2026-02-20T06:48:46.405+05:30","updated":"2026-02-24T10:30:58.984+05:30"}
---


# week 6
- [[#Loop structure]]
	- [[#For loop]]
		- [[#Range function]]
			- [[#1) range(stop)]]
			- [[#2) range(start, stop)]]
			- [[#3) range(start, stop, step)]]
	- [[#While loops]]
	- [[#Nested loops]]
	- [[#Manipulating loop flow]]
		- [[#Break statement `break`]]
		- [[#Continue statement `continue`]]
# Loop structure
A programming construct that repeats a block of code multiple times until a specific condition is met.

![](https://learn.microsoft.com/en-us/dotnet/visual-basic/programming-guide/language-features/control-flow/media/loop-structures/do-until-loop-true-condition.gif)


- Python has 2 loop structures
	- For loop
	- While loop

## For loop

used to iterate over  sequence of values

#### Syntax
```python
for value in sequence: # value is the iterating variable
	statement 1
	statement 2
	...
```

#### Examples

code
```python
numbers = [1,2,3,4,5]
for val in numbers:
	print(val)
```

![](https://www.scaler.com/topics/media/elements-in-python-list-1024x495.webp)

output
```
1 
2
3
4
5
```

### Range function
can be used in 3 different ways

![](https://miro.medium.com/v2/resize:fit:1400/1*IKeh1caojN0BRX1FFvG28g.png)

#### 1) range(stop)

start -> 0
stop -> (stop-1)

```python
>>> list(range(5))
[0, 1, 2, 3, 4]
```

#### 2) range(start, stop)

start -> start
stop -> (stop-1)

```python
>>> list(range(1, 6))
[1, 2, 3, 4, 5]
```

#### 3) range(start, stop, step)

start -> start
stop -> (stop-1)
step -> `step` increment (or decrement). The `step` cannot be zero.

```python
# Positive step to count odd numbers
>>> list(range(1, 10, 2))
[1, 3, 5, 7, 9]

# Negative step to count backwards
>>> list(range(5, 0, -1))
[5, 4, 3, 2, 1]

```

#### Examples

code
```python
sum = 0

for x in range(1,21):
	sum = sum + x

print(sum)

```

output
```
210 # (1+2+3+...+19+20)
```

## While loops

repeats a block of statements as long as a condition is true

![](https://beginnersbook.com/wp-content/uploads/2017/08/while_loop_cpp.jpg)

#### Syntax
```python
while condition:
	statement 1
	statement 2
	inceement or decrement 
	...
```

#### Examples

code (while loop)
```python
x = 4

while x>0:
	print(x)
	x = x-1
```

code (for loop)
```python
for x in range(4, 0, -1):
    print(x)
```

output
```
4
3
2
1
```

code
```python
num = int(input('Enter a number: '))

while num > 0:
	print('Num :' , num) # adds a space automatically
	num = int(input('Enter a number: '))
print('Exit')
```

This program is intended to repeatedly ask for a number and print it back to the user until a non-positive number (like 0 or -1) is entered.

## Nested loops

A loop that is inside another loop

#### Examples

code
```python
for hour in range(12): # 0,1,2,...,10,11
	for minute in range(0,60,15): # 0,15,30,45
		print(hour, ':', minute)
```

output
```
0 : 0
0 : 15
0 : 30
0 : 45
1 : 0
1 : 15
1 : 30
1 : 45
2 : 0
2 : 15
2 : 30
2 : 45
.
.
.
11 : 0
11 : 15
11 : 30
11 : 45
```

## Manipulating loop flow

when we want to alter the normal loop control flow

- ending loop early
- skip some iterations

### Break statement `break`

used to terminate a loop abruptly

code
```python
for x in range (10):
	print(x)
	if(x==3):
		break # exit form the loop immediately 
print('Program ended...')
```

output
```
0
1
2
3
Program ended...
```

### Continue statement `continue`

Causes the program to skip the rest of the loop body in the ==current iteration==.

code
```python
for i in range(-2,3): # -2, -1, 0, 1, 2
	if i == 0:
		continue # skip only 0 iteration (5/0 = infinity)
	print(5/i)
```

output
```
-2.5 # 5/-2
-5.0 # 5/-1
5.0 # 5/1
2.5 # 5/2
```

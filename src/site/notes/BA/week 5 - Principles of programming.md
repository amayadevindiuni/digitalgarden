---
{"dg-publish":true,"permalink":"/ba/week-5-principles-of-programming/","title":"week 5 - Principles of programming","created":"2026-02-17T08:23:32.187+05:30","updated":"2026-02-17T10:34:13.360+05:30"}
---


# week 5
[[#Control flows]]
	- [[#1. Selection (Conditional/If-Else)]]
			- [[#1.1 If]]
			- [[#1.2 If-else]]
			- [[#1.3 If - elif(else +if) - else]]
			- [[#1.4 Nested if]]

# Control flows

control flows:

- selection(if-else
- repetition(loop)
- Subprogram

## 1. Selection (Conditional/If-Else)

Controls which code executes based on conditions.

In flow charts, diamonds are used to represent a true/false condition.

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20230220123250/flowchart_of_if_else_in_c.png"  width="60%" >
### 1.1 If
#### Syntax:
```Python
if expression:
	statement
	statement
	...
```

- After the `if expression`, put a `:` (colon) 
- Each line inside the `if-body` is `indented` by the same amount
- if body is executed only if the expression is True.
	- zero --> false
	- non-zero values --> True
#### Example:
```python
amount = ... # 1000 , 500

if amount > 1000:
	print('You have a discount')
print(amount)
```

- `if-block`: only executed if amount is greater than 1000
- `print(amount)`: outside the scope of the if block, so if block will end there 

### 1.2 If-else 

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20230220123250/flowchart_of_if_else_in_c.png"  width="60%" >

#### Syntax:
```Python
if expression:
	statement(s)
else:
	statement (s)
```

- After the `if expression` and `else`, put a `:` (colon) 
- Each line inside the `if-body` and `else-body` is `indented` by the same amount
- Only either if-body or else-body gets executed, not both
#### Examples:
```python
amount = ... # 1000 , 500

if amount > 1000:
	discount = amount*0.10
else:
	disount = amount*0.05
print(discount)
```

- `if-block`: only executed if amount is greater than 1000
- `else-block`: only executed if amount is less than or equal to 1000 

```python
name = ... # 'Perera'
gender = ... # 'male' , 'female'

if gender == 'male':
	print('Mr. ' + name) # string concatenation 
else:
	print('Ms. ' + name) # string concatenation 
```

### 1.3 If - elif(else +if) - else

#### Syntax:
```Python
if expression_1:
	statement(s)
elif expression_2:
	statement (s)
elif expression_3:
	statement (s)

...
else:
	statement (s)
```

- can use any number of `elif`s but at last there must be a `else`
- conditions are executed from top to bottom, until one condition is satisfied.

#### Example:
```python
amount = ... # 1000 , 500 , 2200

if amount > 2000:
	discount = amount*0.20
elif amount > 1000:
	discount = amount*0.10
else:
	disount = amount*0.05
print(discount)
```

- `if-block`: only executed if amount is greater than 2000
- `elif-block`: only executed if amount is greater than 1000 and less than or equal to 2000 
- `else-block`: only executed if amount is less than or equal to 1000 

### 1.4 Nested if

if structure inside another if structure

#### Syntax:
```Python
if expression_1:
	statement(s)
	if expression_2: # start of inner if-elif-else
		statement (s)
	elif expression_3:
		statement (s)
	else:
		statement (s) # end of inner if-elif-else
else:
	statement (s)
```

- Each line inside the `if-body` is `indented` by the same amount

#### Example:
```python
gender = ... # 'male' , 'female'
name = ... # 'Perera'
married = ... # True , False

if gender == 'female':
	if married == True:
		print('Mrs. ' + name)
	else:
		print('Miss ' + name)
else:
	print('Mr. ' + name)
```

- Outer `if-block`: executed if gender is 'female' 
- Inner `if-block`: executed if gender is 'female' and married is True 
- Inner `else-block`: executed if gender is 'female' and married is False 
- Outer `else-block`: executed if gender is not 'female'

Same example ==without nested if== 
```python
gender = ... # 'male' , 'female'
name = ... # 'Perera'
married = ... # True , False

if gender == 'female' and married == True:
	print('Mrs. ' + name)
elif gender == 'female' and married == False:
	print('Miss. ' + name)
else:
	print('Mr. ' + name)
```

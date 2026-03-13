---
{"dg-publish":true,"permalink":"/ba/week-4-principles-of-programming/","title":"week 4 - Principles of Programming","tags":["lecture",{"{ topic }":null}],"created":"2026-02-10T08:46:48.585+05:30","updated":"2026-03-13T06:27:14.176+05:30"}
---


# Data Types
- numbers
	- integers
	- long integers
	- floating point numbers
	- complex numbers
- strings
- Booleans

## Numbers

### 1. Integers (int)

- Integers are whole numbers without a decimal point. 
- from 0 up to $2^{32}$

```python
x = 42
y = -17
z = 0
```

### 2. Long Integers (long)

- use to store integer values more than $2^{32}$
- cab have an unlimited size value

```python
x = 100  # just an integer, but with unlimited precision
```

### 3.Floating Point Numbers (float)

- Floating point numbers represent real numbers with a decimal point.
- Can be written in standard or scientific notation

```python
a = 3.14
b = -0.001
c = 2.0
d = 1.23e-4  # Scientific notation: 1.23 × 10^-4

# Converting to float
x = float(5)  # 5.0
y = float("3.14")  # 3.14
```

**Precision considerations:**

```python
# Floating point arithmetic may have precision issues
print(0.1 + 0.2)  # 0.30000000000000004 (not exactly 0.3)
```

### 4.Complex Numbers (complex)

Complex numbers have a real and imaginary part. They are written with a 'j' or 'J' suffix to denote the imaginary component.

```python
# Creating complex numbers
z1 = 3 + 4j
z2 = complex(3, 4)  # Same as 3 + 4j
z3 = 2j  # Pure imaginary number

# Accessing components
print(z1.real)  # 3.0
print(z1.imag)  # 4.0

# Complex arithmetic
z4 = (2 + 3j) + (1 + 2j)  # 3 + 5j
z5 = (2 + 3j) * (1 + 2j)  # -4 + 7j
```

## Checking Types

You can check the data type of a variable using `type()` 

```python
x = 42
print(type(x))  # <type 'int'>

print(type(3.14))  # <type 'float'>

z = 2 + 3j
print(type(z))  # <type 'complex'>
```

## Strings

- sequences of characters
- anything inside quotes are considered a string in python
	==''  - single quotes
	"" - double quotes==

 ```python 
# Single quotes 
str1 = 'Hello, World!' 

# Double quotes 
str2 = "Hello, World!" 

# Triple quotes (for multi-line strings) 
str3 = '''This is a 
multi-line string''' 
str4 = """This is 
also a 
multi-line string""" 

# Empty string 
empty = '' 
 ```

## Booleans

- only two values
		==False==
		==True==
- don't use quotes, it will become a string

```Python
is_raining = True
is_sunny = False

print(is_raining) # True
print(is_sunny) # False
```
# Expressions

An expression is a combination of values, variables, operators, and function calls that Python evaluates to produce a result.

![](https://www.techtarget.com/rms/onlineimages/operand_vs_operator-h_half_column_mobile.png)

### Arithmetic operators

![](https://www.devopsschool.com/blog/wp-content/uploads/2020/08/arithmetic-operation-in-python.png)

#### Addition (+)

```python
# Adding two numbers
a = 5
b = 3
result = a + b
print(result)  # Output: 8

# Adding multiple numbers
total = 10 + 20 + 30
print(total)  # Output: 60

# Adding integers and floats
sum1 = 5 + 2.5
print(sum1)  # Output: 7.5
```

#### Subtraction (-)

```python
# Subtracting two numbers
a = 10
b = 4
result = a - b
print(result)  # Output: 6

# Negative result
result = 5 - 8
print(result)  # Output: -3

# Subtracting floats
result = 10.5 - 3.2
print(result)  # Output: 7.3
```

#### Multiplication (\*)

```python
# Multiplying two numbers
a = 6
b = 7
result = a * b
print(result)  # Output: 42

# Multiplying by zero
result = 100 * 0
print(result)  # Output: 0

# Multiplying floats
result = 2.5 * 4
print(result)  # Output: 10.0
```

#### Division (/)

```python
# Dividing two numbers (always returns float)
a = 10
b = 2
result = a / b
print(result)  # Output: 5.0

# Division with remainder
result = 7 / 2
print(result)  # Output: 3.5

# Dividing floats
result = 9.6 / 3.2
print(result)  # Output: 3.0
```

#### Floor Division (//)

```python
# Floor division (rounds down to nearest integer)
a = 10
b = 3
result = a // b
print(result)  # Output: 3

# Floor division with floats
result = 10.0 // 3.0
print(result)  # Output: 3.0

# Negative floor division
result = -10 // 3
print(result)  # Output: -4 (rounds down)
```

#### Modulus (%)

```python
# Finding remainder
a = 10
b = 3
result = a % b
print(result)  # Output: 1

# Check if number is even
number = 8
remainder = number % 2
print(remainder)  # Output: 0 (even numbers have remainder 0)

# Check if number is odd
number = 7
remainder = number % 2
print(remainder)  # Output: 1 (odd numbers have remainder 1)
```

#### Exponentiation (\*\*)

```python
# Raising to a power
a = 2
b = 3
result = a ** b  # 2 to the power of 3
print(result)  # Output: 8

# Square of a number
number = 5
square = number ** 2
print(square)  # Output: 25

# Cube of a number
number = 3
cube = number ** 3
print(cube)  # Output: 27

# Square root (using power of 0.5)
number = 16
sqrt = number ** 0.5
print(sqrt)  # Output: 4.0
```

### String operators

#### String Concatenation (Joining Strings)

##### Using + Operator

```python
# Joining two strings
first_name = "John"
last_name = "Doe"
full_name = first_name + " " + last_name
print(full_name)  # Output: John Doe

# Joining multiple strings
greeting = "Hello" + " " + "World" + "!"
print(greeting)  # Output: Hello World!

# Building a sentence
subject = "Python"
verb = "is"
adjective = "awesome"
sentence = subject + " " + verb + " " + adjective
print(sentence)  # Output: Python is awesome
```


#### String Repetition

```python
# Repeating a string
star = "*"
line = star * 10
print(line)  # Output: **********

# Creating separator
separator = "-" * 20
print(separator)  # Output: --------------------

# Repeating words
laugh = "Ha" * 3
print(laugh)  # Output: HaHaHa

# Multiple repetitions
pattern = "ABC" * 4
print(pattern)  # Output: ABCABCABCABC
```

### Comparison Operators
- output is always a Boolean 

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQaeiIMFlun2hyVE9cIw8tUa3pHiTw85uyM6A&s)

- in python earlier versions `<>` was used as not equal

```Python
# Two numbers for comparison
a = 10
b = 5

print("a =", a)
print("b =", b)
print()

# Equal to (==)
print("a == b:", a == b)
# Output: a == b: False

# Not equal to (!=)
print("a != b:", a != b)
# Output: a != b: True

# Greater than (>)
print("a > b:", a > b)
# Output: a > b: True

# Less than (<)
print("a < b:", a < b)
# Output: a < b: False

# Greater than or equal to (>=)
print("a >= b:", a >= b)
# Output: a >= b: True

# Less than or equal to (<=)
print("a <= b:", a <= b)
# Output: a <= b: False
```

### Logical operators

- used to combine Boolean value expressions and give a Boolean result

| Operator | Name        | Example          | Result  |
| -------- | ----------- | ---------------- | ------- |
| `and`    | Logical AND | `True and False` | `False` |
| `or`     | Logical OR  | `True or False`  | `True`  |
| `not`    | Logical NOT | `not True`       | `False` |

```python
# Two boolean values for demonstration
a = True
b = False

print("a =", a)
print("b =", b)
print()

# AND operator (True if both are True)
print("a and b:", a and b)
# Output: a and b: False

# OR operator (True if at least one is True)
print("a or b:", a or b)
# Output: a or b: True

# NOT operator (Inverts the boolean value)
print("not a:", not a)
# Output: not a: False

print("not b:", not b)
# Output: not b: True
```

### Assignment operators

| Operator | Name                    | Example   | Equivalent To | Result    |
| -------- | ----------------------- | --------- | ------------- | --------- |
| `=`      | Assignment              | `x = 5`   | -             | `x = 5`   |
| `+=`     | Add and assign          | `x += 3`  | `x = x + 3`   | `x = 8`   |
| `-=`     | Subtract and assign     | `x -= 2`  | `x = x - 2`   | `x = 6`   |
| `*=`     | Multiply and assign     | `x *= 4`  | `x = x * 4`   | `x = 24`  |
| `/=`     | Divide and assign       | `x /= 3`  | `x = x / 3`   | `x = 8.0` |
| `//=`    | Floor divide and assign | `x //= 2` | `x = x // 2`  | `x = 4.0` |
| `%=`     | Modulus and assign      | `x %= 3`  | `x = x % 3`   | `x = 1.0` |
| `**=`    | Exponent and assign     | `x **= 2` | `x = x ** 2`  | `x = 1.0` |

```python 
# Simple Assignment 
x = 10 
print(x) # 10 

# Addition Assignment 
x = 10 
x += 5 # Same as: x = x + 5 
print(x) # 15 

# Multiplication Assignment 
x = 10 
x *= 2 # Same as: x = x * 2 
print(x) # 20 
```

# Operator Precedence

- Parentheses () comes first and are used to change the order.

![](https://i.postimg.cc/cH9zBgR2/Whats-App-Image-2026-02-10-at-10-07-01-AM.jpg)

- But **exponent** is solved **right to left**

```Python
# Right-to-left evaluation
result_right_to_left = 2 ** 3 ** 2

# Step 1: Calculate the rightmost exponent (3 ** 2)
# 3 ** 2 = 9

# Step 2: Calculate the remaining exponent (2 ** 9)
# 2 ** 9 = 512

print(f"2 ** 3 ** 2 evaluates to: {result_right_to_left}")
# Output: 2 ** 3 ** 2 evaluates to: 512

```

- **Same level operations** are solved **left to right**

```Python
# Subtraction and Addition have the same precedence
result = 5 - 2 + 3 
# Left-to-right: (5 - 2) + 3 = 3 + 3 = 6
print(result) # Output: 6

```

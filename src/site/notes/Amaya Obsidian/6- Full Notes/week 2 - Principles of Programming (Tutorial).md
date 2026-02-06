---
{"dg-publish":true,"permalink":"/amaya-obsidian/6-full-notes/week-2-principles-of-programming-tutorial/","title":"week 2 - Principles of Programming (Tutorial)","tags":["lecture",{"{ topic }":null},"gardenEntry"],"created":"2026-01-18T21:23:11.465+05:30","updated":"2026-02-06T18:36:52.521+05:30"}
---


# week 2 (Tutorial)

[[#Steps to follow]]

[[#More on Variables]]
- [[#Strings in variables]]
- [[#When the string contains quotes]]
- [[#Boolean values in variables]]
- [[#Print variables and strings together]]
- [[#Print arithmetic operation]]

# Steps to follow
## 1. Open notepad
![](https://i.postimg.cc/vBmkCKmL/image.png)
## 2. Type this code
```
x = 5
prit(x)
```

## 3. Save the file with ==.py== extension and  a name
![](https://i.postimg.cc/FsN8QwqW/image.png)
## 4. Search ==cmd== or command prompt
## 5. Go to file path using ==cd command==

```
cd file_path
```

- If you cannot find the path, right click on your file and select copy as path, then paste the path to cmd

## 6. Run the file using cmd

- Type
```
python file_name.py
```

- Hit Enter

output:
```
5
```

- Change the variable numbers and run the file again

# More on Variables
## Strings in variables
- Use single quotes ==''== or double quotes ==""== to store strings

code:
```
first_name = 'your_name'
print(first_name)
```

output:
```
your_name
```

## When the string contains quotes
- Use Opposite Quotes

code:
```
msg = "It's Tuesday"
print(msg)
```

output:
```
It's Tuesday
```

## Boolean values in variables
- Only two values 
```
True
False
```

code:
```
bool = True
print(bool)
```

output:
```
True
```

## Print variables and strings together
code:
```
name = "Dishani"
print("I'm " + name + " and " + name + " is the instructor")
```
output:
```
I'm Dishani and Dishani is the instructor
```

## Print arithmetic operations
code:
```
x = 4
y = 5

print(x + y)
print(x - y)
print(x * y)
print(x / y)
```

output:
```
9
-1
20
0.8
```

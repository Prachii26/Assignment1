# ASSIGNMENT 1
Module 2: Basic Python Concepts

## Task 1

Perform Basic Mathematical Operations
1.  Takes two numbers as input from the user.
2.  Performs the basic mathematical operations on these two numbers.
3.  Displays the results of each operation on the screen.


### Code

```python
# takes first input as integer
a=int(input('Enter the first number: '))

# takes second input as integer
b=int(input('Enter the second number: '))

#Addition
print('Addition: ', a+b )
#Subtraction
print('Subtraction: ', a-b )
#Multiplication
print('Multiplication: ', a*b )
#Division
print('Division: ', a/b )
```

### Output
```
Enter the first number: 5
Enter the second number: 10
Addition:  15
Subtraction:  -5
Multiplication:  50
Division:  0.5
```


## Task 2

Write a Python program that:
1.  Takes a user's first name and last name as input.
2.  Concatenates the first name and last name into a full name.
3.  Prints a personalized greeting message using the full name.

### Code

```python
# takes first name as input
a=input('Enter your first name: ')

# takes second name as input
b=input('Enter your second name: ')

#print the required message
print("Hello, " + a + " " + b +"! Welcome to the Python program.")

```

### Output
```
Enter your first name: John
Enter your second name: Doe
Hello, John Doe! Welcome to the Python program.
```

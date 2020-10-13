# Day 2 Class Notes

## What was covered
- Assigning Variables
- Manipulating Numbers
- Manipulating Strings
- Booleans and Conditionals

### Variables
Variables are a method where data cached in memory that is pointed at some 'thing'.
Like math, you assign a variable by giving it a *"Name"* on the left hand side (LHS) and setting it equal to *=* the right hand side (RHS).
For instance:

```python
#Varaible getting the value of the string 'Hello World'
# = is the assignment operator
message = "Hello World" 
print(message) 
# The Variable is using the value assigned to it.
```
Words, or rather, *strings* aren't the only thing that can be assigned. Numbers and booleans (Truthy or Falsy) are capable of being given a variable assignment.

### Numbers
Numbers fall in to two categories; *integers* and *floats*. 

- ```python
    #integers
    1
    123
    -234
    0
- ```python
    #floats
    1.3
    4.5
    -23233.774345

    To manipualte those numbers, Python has built mathematical operators to help perform whatever calculation you need. 
    - ```python
    3+2 #addition
    3-2 #subtraction
    3*2 #multiplication
    3/2 #division
    3+2*3/2 #order of operation

Further more, you can assign those numbers to a variable and manipulate the numbers through that assignment and print to console your output

- ```python
a = 100
b = 200
print(a + b) # 300
print(a - b) # -100
print(a / b) # 1/2
print(a * b) # 20000
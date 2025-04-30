# 19CS301-Module2
Exp.No:2(a)	ITERATIVE STATEMENTS- PRINTING1 TO N EVEN NUMBERS
### AIM
To create a python program for printing 1 to n even numbers.

### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Get the input to an integer

Step 3:	 Use a for loop to iterate from 1 to n (inclusive).

Step 4:	If number % 2 == 0 (i.e., the number is divisible by 2),Print the number.	 

Step 5:	 In each iteration, print the current value of i.

Step 6:	 Terminate the program.

### PROGRAM
```
Even = int(input())
for number in range(1,Even+1):
    if(number % 2 == 0):
        print(number)
```
### OUTPUT
![image](https://github.com/23013357/19CS301-Module2/blob/main/tt.png)

 
### RESULT
Thus the python program for printing 1 to n even numbers has been implemented and executed successfully.

Exp.No:2(b)	FUNCTIONS-MEAN OF 3 NUMBERS

### AIM
To write a Python Program to check if a number is a Perfect number using the concept of functions.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	Input the first number and store it in variable a.

Step 3:	 Input the second number and store it in variable b.

Step 4:	 Input the third number and store it in variable c..

Step 5:	 Calculate the sum: d = a + b + c.

Step 6:	Calculate the mean: mean = d / 3.

Step 7:	Display the value of mean.

Step 8:	 Terminate the program.
### PROGRAM
```
def result(a,b,c):
    d=a+b+c
    mean=(a+b+c)/3
    
    print(f"mean is {mean}")

a = int(input())
b = int(input())
c = int(input())


```
### OUTPUT
 ![image](https://github.com/23013357/19CS301-Module2/blob/main/yy.png)

### RESULT
Thus the python program to steps to calculate the mean of three Numbers
Start the program has been implemented and executed successfully.

Exp.No:2(c)	BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS- CALCULATE THE EXPRESSION

### AIM
To write a  program in Python to calculate the value of the following expression by using lambda function.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Use eval() to get the three numbers (num1,num2 and num2) from the user.

Step 3:	 Define a lambda function res that takes three arguments x,y and z.

Step 4:	 Define an expression: (x / 10) * (y / 2) * z.

Step 5:	 Display the result.

Step 6:	 Terminate the program.
### PROGRAM
```
x=int(input())
y=int(input())
z=int(input())

expr = lambda x, y, z: (x/10) * (y/2) * z
print(expr(x, y, z))
```
### OUTPUT
![image](https://github.com/user-attachments/assets/d6767aa8-b158-4f19-83f6-af03322a5b9d)


### RESULT
Thus the python program to check a relationship between two numbers has been implemented and executed successfully.


Exp.No:2(d)	LOOPING PATTERNS- PRINTING PATTERN

### AIM
To write a python program to print the triangular star pattern.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Read the integer n from the user using input(). This will determine the number of rows in the pattern.

Step 3:	 Initialize a variable i = 0. This will be used to control the number of spaces before the stars.

Step 4:	 Loop through rows from 0 to n-1 (this will iterate n times to print the required rows).

Step 5:	  For each row, calculate the number of spaces before the stars. 

Step 6:	 The formula for the number of spaces is ((n - rows - 1) * 2) + i. 

Step 7:	 Print the spaces (" ") using the print(" ", end="") statement. 

Step 8:	 Increment i by 1 after each row.

Step 9:	 For each row, print the stars. The number of stars for each row is equal to rows + 1. Print the stars with print("*", end=" ") to separate them with two spaces.

Step 10:	 After printing each row's stars, print a newline to move to the next row using print("").

Step 11:	 Terminate the program.
### PROGRAM
```n=int(input())
i=0
for rows in range(0,n):
    for cols in range(((n-rows-1)*2)+i):
        print(" ",end="")
    i+=1
    for star in range(rows+1):
        print("*",end="  ")
    print("")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/97a7d6f9-97f1-44e6-a8b1-2c110a717d1c)


 
### RESULT
Thus the python program to print the triangular start pattern has been implemented and executed successfully.
























Exp.No:2(e)	SEB- COMPUTING POWER

### AIM
To write a python Program to compute the power of the given number using appropriate built -in function .
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Input the base number (base) from the user.

Step 3:	 Input the exponent number (exp) from the user.

Step 4:	 Use the built-in pow() function to compute the  base raised to the power of exp.

Step 5:	 Print the result using the print() function, displaying the power of the given number in a formatted manner.

Step 6:	 Terminate the program.
### PROGRAM
```base=int(input())
exp=int(input())
res=pow(base,exp)
print(f"Power of the given number is: {res}")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/f0c61287-b7a6-4c76-908d-396f4104d75b)

 

### RESULT
Thus the python program to compute the power using builtin function has been implemented and executed successfully.






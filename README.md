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
![image](https://github.com/23013357/19CS301-Module2/blob/main/uu.png)


### RESULT
Thus the python program to checking the expression has been implemented and executed successfully.


Exp.No:2(d)	LOOPING PATTERNS- PRINTING PATTERN

### AIM
To write a python program to print the triangular star pattern.
### ALGORITHM

step 1:Start the program.

step 2:Input the number of rows (integer) and store it in variable rows.

step 3:Start a loop to iterate from i = 0 to i = rows - 1:

step 4:For each i (representing the current row number):

step 5:Start a nested loop to iterate from j = 0 to j = i:

step 6:Print a star (*) followed by a space on the same line.

step 7:After completing the inner loop for each row, print a newline to move to the next row.

step 8:End the program.
### PROGRAM
```
rows=int(input())
for i in range(0, rows):
    for j in range(0, i+1):
        print("*", end=' ')
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






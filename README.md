Printing Rhombus Star Pattern
In this Python Program, we will be discussing about how to write a program to print Rhombus Star Pattern. A rhombus is a quadrilateral whose four sides all have the same length. So, In this pattern, numbers of rows and equal number of columns are present. So, User have to enter a single value, that will be determine as a number of rows and columns of the pattern.

Python Program for Rhombus Star Pattern
Working:
Step 1. Start

Step 2. Take number of rows as input from the user and stored it into num.

Step 3. Run a for loop starting from 0 to user entered num value.

Step 4. Inside for loop, Run two for loops where one for printing space and one for printing star for pattern.

Step 5. Move to the next line by printing a new line using print() function.

Stop 6. Stop

Python Program:
num = int(input("Enter the number:"))

for i in range(0, num):
    for j in range(1, i+1):
        print(" ", end="")
    for j in range(0, num):
        print("*", end="")
    print()

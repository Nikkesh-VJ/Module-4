- **Name:** Nikkesh V  
- **Registration Number:** 212222050042
# 19CS301-Module-4
ExNo.4a DICTIONARY- SIZE OF DICTIONARY
### AIM
To write a  python program to print the size of dictionary using getsizeof() from sys module.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	  Import the sys module to access the getsizeof() function.

Step 3:	 Define dictionaries with necessary values.

Step 4:	 Use sys.getsizeof(dic1) to get the size of dic1,dic2,dic3.

Step 5:	  Print the size value of dic1, dic2,dic3.

Step 6:	 Terminate the program.

### PROGRAM
```import sys
dic1 = {"A": 1, "B": 2, "C": 3}
dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}
print(f"Size of dic1: {sys.getsizeof(dic1)}bytes")
print(f"Size of dic2: {sys.getsizeof(dic2)}bytes")
print(f"Size of dic3: {sys.getsizeof(dic3)}bytes")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/c04d58b1-b6a9-4753-a88e-db8914bc73c6)

 
### RESULT
Thus the python program for printing a size of dictionary, was implemented and executed successfully.

Exp.No:4(b)	EXCEPTION- EXCEPTION HANDLING
### AIM
To create a short program that prompts the user for a list of grades separated by commas, Split the string into individual grades and use a list comprehension to convert each string to an integer, use a try statement to inform the user when the values they entered cannot be converted.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Read a string from the user using input() and store it in input_str.

Step 3:	 Split the input_str using commas (,) to create a list of grades.

Step 4:	 Use a try block to attempt converting each item in the grades list to an integer and store the result in l1. If an error occurs, proceed to step 6.

Step 5:	 If the conversion is successful, print the list l1 containing the integer values.

Step 6:	 If there is an error during conversion (for example, if the input is not a valid number), print an error message "The grades you entered were in an invalid format." and print 
         the original grades list.

Step 7:	 Terminate the program.
### PROGRAM
```input_str=input()
grades=input_str.split(',')
try:
    l1=[int(item) for item in grades]
except:
    print("The grades you entered were in an invalid format.")
    print(grades)
else:
    l1=[int(item) for item in grades]
    print(l1)
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/86726500-ef3e-4a14-a878-cb7b5c0886c5)

### RESULT
Thus the python program for handling exceptions was implemented and executed successfully.

EXNo.4C File Handling -Count the frequency of each character in a File
### AIM
To write a Python program to read a file and count the frequency of each character in it.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Define the function create file  andAccept two arguments: file_path (the path to the file) and content (the string content to be written into the file).

Step 3:	 Open the file specified by file_path in write mode ('w'), Write the provided content to the file.

Step 4:	Close the file (this is done automatically when exiting the with block).

Step 5:	 Define the function character frequency,Accept one argument: file_path (the path to the file whose character frequency is to be calculated).

Step 6:	 Open the file specified by file_path in read mode ('r'), Read the content of the file into the variable content.

Step 7:	 Initialize an empty defaultdict of type int (which will store the frequency of each character).

Step 8:	 Loop through each character in the content: For each character ch, increment its corresponding frequency in the dictionary d1.

Step 9:	 Return the dictionary d1, which contains the frequency of each character in the file.

Step 10:	 Terminate the program.
### PROGRAM
```
input_str=input()
grades=input_str.split(',')
try:
    l1=[int(item) for item in grades]
except:
    print("The grades you entered were in an invalid format.")
    print(grades)
else:
    l1=[int(item) for item in grades]
    print(l1)
```
### OUTPUT

 ![image](https://github.com/user-attachments/assets/a23ca630-bc9b-439a-b4f1-fcad2a2e0711)

 
### RESULT
Thus the python program for finding character frequency count in a file, was implemented and executed successfully.

ExNo.4(d). CLASS AND OBJECTS- AREA OF CIRCLE

### AIM
To write Python Program to take the radius from the user and find the area of the circle using class name 'umbrella' and function name 'rain'
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	  Create a class named umbrella.

Step 3:	 Define a method rain(self, r) that accepts a radius r as an argument.

Step 4:	 Inside the rain method: Calculate the area of a circle using the formula: Area = π * r^2. Use the math.pi constant to get the value of π and perform the calculation. Print the 
          result, formatted to two decimal places.

Step 5:	 Prompt the user for an integer input to represent the radius of the circle.

Step 6:	 Create an instance of the umbrella class and store it in the variable u.

Step 7:	 Call the rain method of the umbrella class, passing the user-provided radius r as an argument.

Step 8:	 Terminate the program.
### PROGRAM
```
import math
class umbrella:
    def rain(self,r):
        res=math.pi * r * r
        print(f"Area of circle: {res:.2f}")
r=int(input())
u=umbrella()
u.rain(r)
```
### OUTPUT
![image](https://github.com/user-attachments/assets/aa51e6ae-8312-4d49-85a6-774bfead5223)

 
### RESULT
Thus the python program for calculating the area of a circle was implemented and executed successfully.

Exp.No:4(e)	SEB- ARITHMETIC CALCULATION USING CLASS

### AIM
To write a python program to perform addition and division operation using class and if,elif..
class name should be saveetha, function name should be setvalues( to set a and b values) add and div.cases : choice 1 ->perform addition ,choice 2-> perform division ,  choice 0 -> exiting, other choices -> print 'invalid choice'
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Create the Saveetha Class.

Step 3:	 Create the main() function.

Step 4:	 Set the values of a and b using the setvalues(a, b) method of the Saveetha object.

Step 5:	 Start a while True loop to repeatedly ask the user for a choice. 

Step 6:	 Take the user's choice (1 for addition, 2 for division, 0 for exit).

Step 7:	 If the choice is 1, call the add() method and print the result (converted to an integer).

Step 8:	 If the choice is 2, call the div() method and print the result (converted to an integer). Handle division by zero.

Step 9:	 If the choice is 0, print "Exiting!" and exit the loop.

Step 10:	 If the choice is not 1, 2, or 0, print "Invalid choice"

Step 11:	   Terminate the program.
### PROGRAM
```class Saveetha:
    def __init__(self):
        self.a = 0
        self.b = 0

    def setvalues(self, a, b):
        self.a = a
        self.b = b

    def add(self):
        return self.a + self.b

    def div(self):
        if self.b != 0:
            return self.a / self.b
        else:
            return "Error: Division by zero"
def main():
    saveetha_obj = Saveetha()
    a = float(input())``
    b = float(input())
    while True:
        saveetha_obj.setvalues(a, b)
        choice = int(input())
        if choice == 1:
            result = saveetha_obj.add()
            print(f"Result:  {int(result)}")
        elif choice == 2:
            result = saveetha_obj.div()
            print(f"Result:  {int(result)}")
        elif choice == 0:
            print("Exiting!")
            break
        else:
            print("Invalid choice")

# Run the main function
main()
```
### OUTPUT
![image](https://github.com/user-attachments/assets/a3851f8f-c387-41ea-81b1-5806c381d653)
 
### RESULT
Thus the arithmetic calculation using class has been  implemented and executed successfully.




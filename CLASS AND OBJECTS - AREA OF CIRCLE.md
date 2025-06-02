# ExNo.4(d). CLASS AND OBJECTS- AREA OF CIRCLE

- **Name:** Nikkesh V  
- **Registration Number:** 212222050042

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

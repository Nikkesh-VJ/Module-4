# Exp.No:4(e)	SEB- ARITHMETIC CALCULATION USING CLASS

- **Name:** Nikkesh V  
- **Registration Number:** 212222050042
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

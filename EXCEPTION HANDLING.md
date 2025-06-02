# Exp.No:4(c)	EXCEPTION- EXCEPTION HANDLING

- **Name:** Nikkesh V  
- **Registration Number:** 212222050042

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

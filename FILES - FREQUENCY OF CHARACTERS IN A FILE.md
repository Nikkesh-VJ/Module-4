# EXNo.4d File Handling -Count the frequency of each character in a File

- **Name:** Nikkesh V  
- **Registration Number:** 212222050042
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

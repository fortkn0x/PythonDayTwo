# Python Day Two

## Review from Yesterday

### Topics Covered

 1. Logical operators  
 2. Data types (String, int, float, boolean)   
 3. Variable assignment
 4. print statements   
 5.  input function
 
## Data types
String: any sequence of characters between DOUBLE quotes
"allison", "purple 967", "hellogoodbye", "4"
Integer: a positive or negative whole number
Float: a positive or negative number (including decimals)
Boolean: a True or False value
*Exercise: given the following variables, determine their datatypes.*

## Variable Declaration
variableName = variableValue
The name can by anything, but the value must be a valid datatype.
The name of a variable represents the value that it stores.

    x = 3
    print(x > 4)
    print(x > 3)
    print(x > 1)
  
  We assign values to variables. Variables can be reassigned. 

    age = 21
    age = age + 1

Exercise: given the following code, what will print out?

    y = 20
    print(y)
    y=14
    print(y)
    print(y+1)
    y=y+1
    print(y)

## Print statements
Functions take in some sort of input and do a set process with that input. The print function takes in what you want to print, and then prints that out to the console.

    print("what i want to print out")
    print(10)
    print(x)

We can include multiple things within a print statement.

 `month = "August"`
` print("The month is " + month)`

Everything within a print statement must be of the same datatype. You will receive an error if you try to add an integer to a string.

    month = 8
    print("The month is " + month)
  
  How can we avoid this? The str() function.
  
 ## Input function
Functions take in some input, do a set process given that input, and return some output. The input function takes in a string that is printed to the console, and *returns* the value the user wrote as a **STRING**.

## Len function 
The len() function takes in an object that is a sequence. A string is a sequence of characters. So the len() function takes in a String and returns the length of a given string.
*Exercise: print(len(word)==10)*

## Control Flow
Code is read from top-to-bottom. That's why when we write y=20 then print(y) and then y= 22 then print(y) it's different.

    if [some Condition is True]:
	    #execute this code
	elif [this is True and previous condition is False]:
		#execute this code
	else: #hidden condition: everything above it is false
		#execute this code
	
Show a simple example of an if statement:

    evenNum = 2
    if evenNum > 0:
	    print(str(evenNum) + " is greater than 0")
	elif evenNum > 1:
		print(str(evenNum) + " is greater than 1")
		

    numEven = 2 
    if numEven > 0:
	    print(str(numEven) + " is greater than 0")
	
	if numEven > 1: 
		print(str(numEven) + " is greater than 1")


Exercise:
Have everyone write an if-elif-else statement. Everyone presents it on google meet and explains why they wrote it the way that they did.

Exercise: Everyone shares a repl, we ask the user to build a website. First, we ask what they want the name of their website to be. Then we ask them to create a username, then we ask them to create a password. The username must have at least 8 characters, and the password must have at least 12 characters.

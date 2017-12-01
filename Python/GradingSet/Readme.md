## Python Basics - Grading Exercise

        Question |  Points  
        ---------|-------------
			01| 10
			02| 10
			03| 10
			04| 10
			05| 5
			06| 10
			07| 10
			08| 5
			09| 5
			10| 5
			11| 10
			12| 10

Notes for Submission
a. Generate one .py file for each Question.
	
b. Follow best coding practices like adding DocString, Try and Except clauses and Defensive Programming techniques.
		
c. Add Testfunctions for questions where you are to check for multiple scenarios.
		
d. Add Unittest functions where necessary.
		
e. All your submissions should be under your git respository like Solutions>Python>ProblemSet01>(Place your files here). Repeat 
for other ProblemSets and GradingSets.

1.	Write a program which takes 2 digits, X,Y as input and generates a 2-dimensional array. The element value in the i-th row and j-th column of the array should be i*j.
	Note: i=0,1.., X-1; j=0,1,¡­Y-1.
	Example
	Suppose the following inputs are given to the program:
	3,5
	Then, the output of the program should be:
	[[0, 0, 0, 0, 0], [0, 1, 2, 3, 4], [0, 2, 4, 6, 8]] 

###Hints:
Note: In case of input data being supplied to the question, it should be assumed to be a console input in a comma-separated form.


2.  Please write a program which counts and prints the numbers of each character in a string input by console.

	Example:
	If the following string is given as input to the program:

	abcdefgabc

	Then, the output of the program should be:

	a,2
	c,2
	b,2
	e,1
	d,1
	g,1
	f,1

###Hints:
	Use dict to store key/value pairs.
	Use dict.get() method to lookup a key with default value.

3.	Write a Program to Implement a the linear search algorithm. Test that it works with items in and not in the list
         (a) Add a counter to report how many searches have been done for each item searched for.
         (b) Add the functionality to add an item to the list if it is not found.

4. 	A website requires the users to input username and password to register. Write a program to check the validity of password input by users.
	Following are the criteria for checking the password:
	1. At least 1 letter between [a-z]
	2. At least 1 number between [0-9]
	1. At least 1 letter between [A-Z]
	3. At least 1 character from [$#@]
	4. Minimum length of transaction password: 6
	5. Maximum length of transaction password: 12
	Your program should accept a sequence of comma separated passwords and will check them according to the above criteria. Passwords that match the criteria are to be printed, each separated by a comma.
Example
	If the following passwords are given as input to the program:
	ABd1234@1,a F1#,2w3E*,2We3345
	Then, the output of the program should be:
	ABd1234@1

###Hints:
In case of input data being supplied to the question, it should be assumed to be a console input.

5. (a)Write a program that will ask the user for a number and then print out a list of number from 1 to the number entered and the square of the number. 
	For example, if the user entered '3' then the program would output:

	1 squared is 1.
	2 squared is 4.
	3 squared is 9.
	
	(b) Alter the program to perform the following
	With a given integral number n, change the program to generate a dictionary that contains (i, cube of i) such that is an integral number between 1 and n (both included). 
		and then the program should print the dictionary.
		Suppose the following input is supplied to the program:
		7
		Then, the output should be:
		{1: 1, 2: 8, 3: 27, 4: 64, 5: 125, 6: 216, 7: 373}
		Take the input from the user via console.

6.(a) Create a program which asks the user for 3 numbers representing the year, month and day e.g 1982 10 08 and then outputs in the form 8th October 1982.
  (b) Write a function greatestCommonDivisor that takes two positive integers and computes their greatest common divisor
	Suppose the following input is supplied to the program:
		2,30
	Then, the output should be:
	The greatest common divisor is 2
	Take the input from the user via console.

7. Write a Python program named Indiastates.py that declares a variable states with value "Maharashtra Assam TamilNadu MadhyaPradesh Karnataka".  
	Write a program that does the following:
	a) Search for a word in variable states that ends in esh. Store this word in element 0 of a list named statesList.
	b) Search for a word in states that begins with t and ends in u. Perform a case-insensitive comparison. 
	   [Note: Passing re.I as a second parameter to method compile performs a case-insensitive comparison.] Store this word in element 1 of statesList.
	c) Search for a word in states that begins with M and ends in a. Store this word in element 2 of the list.
	d) Search for a word in states that ends in a. Store this word in element 3 of the list.
	e) Search for a word that begins with M in states at the beginning of the string. Store this word at element 4 of the list.
	f) Output the array statesList to the screen.

###Hints:
In case of input data being supplied to the question, it should be assumed to be a console input.
Use list enumeration for sorting where necessary.

8. 	Write a one- to three-line block of code for each of the following tasks:
		a) Create a string with 50 exclamation points (!) using the * operator.
		b) Print out even numbers from 0 to 100.
		c) Convert a user-entered number from a string to an integer.
		d) Determine whether a user-entered integer is odd. Come out with a Common Message "Entry Validated".(Do not display any thing for even.)
		e) Concatenate an empty tuple and a singleton with the += statement.
		f) Perform Mutable operation on a List and also append using += statement.

9. 	Use a list comprehension to square each odd number in a list. The list is input by a sequence of comma-separated numbers.
	Suppose the following input is supplied to the program:
	1,2,3,4,5,6,7,8,9
	Then, the output should be:
	1,3,5,7,9

###Hints:
	In case of input data being supplied to the question, it should be assumed to be a console input.

10.	The Fibonacci Sequence is computed based on the following formula:

	f(n)=0 if n=0
	f(n)=1 if n=1
	f(n)=f(n-1)+f(n-2) if n>1

	Please write a program using list comprehension to print the Fibonacci Sequence in comma separated form with a given n input by console.

	Example:
	If the following n is given as input to the program:

	7

	Then, the output of the program should be:

	0,1,1,2,3,5,8,13


	Hints:
	We can define recursive function in Python.
	Use list comprehension to generate a list from an existing list.
	Use string.join() to join a list of strings.

	In case of input data being supplied to the question, it should be assumed to be a console input.

11.	Create a file with the following matrix X:
	1 2
	3 4
	Read and then compute Y = 2 * X. 

	Read another file with a Matrix Z: 
	1 2
	4 4
	Read and then Compute(Matrix Mutilication) Y = X * Z

12. Write a Python program to connect to a SQLite DB and Create table employees in it.

 	CREATE TABLE employees ID, Firstname,LastName,Dept.
 
	Data:          
 	100, 'Sunil','Shetty', 'Cinema'
 	200, 'Srini','Mahalingam', 'IT'
 	300, 'Adam','Sanders', 'IT'
 	400, 'Tommy','Mancenty', 'Guild'
 	500, 'Hovis','M', NULL
	
	Add 3 more employees records under each department.
	a) Read and display the records.
	b) Generate a report for Department 'Guild' 
	c) Update all 'IT' Dept Employees to <User Provided Dept>. Get the department to be changed from the User.
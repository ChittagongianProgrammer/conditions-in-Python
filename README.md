# Conditionals in Python
Here is an explanation of the code in the two Jupyter notebook (.ipynb) files:

## conditionals.ipynb

This notebook provides examples of using conditional statements like if, elif, and else in Python.

### Conditional Statements section

- An age variable is taken as user input.
- An if statement checks if age >= 100, and prints a message that the user is too old to join.
- An elif checks if age >= 18 and prints a message that the user can join.
- Another elif checks if age < 0 to catch invalid input. 
- An else statement prints a message that the user must be over 18 to join.

### Customer Service Example 

- A response variable takes user input asking if they need help.
- An if statement checks if the response is "Y" and offers help.
- An elif checks if response is "N" and says to ask if they change their mind.
- An else catches invalid responses.

### Boolean Example

- An offline variable is set to True  
- If offline is True, it prints not to add them.
- Else prints to add them to the lobby.

## python_calculator.ipynb

This implements a simple calculator application with different math operations.

- It imports math library to use math functions.
- It takes an operation input from user - options like +, -, *, /, abs, **, sqr.
- For each operation, it takes numerical inputs and performs operation to print output.
- Checks for divide by 0 error and invalid operators. 
- Uses if, elif conditional checks to pick the operation.
- Prints output rounded to 3 decimal places.


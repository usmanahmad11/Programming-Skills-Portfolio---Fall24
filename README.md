
# Assessment 1 - Programming-Skills-Portfolio
Your task is to develop solutions to a series of coding exercises that will test your knowledge of the
fundamental programming techniques introduced through the course of the module. These exercises
complement the content delivered in class each week and allow you to put into practice what you have
learned.
When completing the exercises you should create a new project for each one and save them to this folder.
Each exercise should be appropriately named (e.g. 01-CodingIsCool) so they are easy to find. You should
commit changes in your repository often (as a minimum after completing each exercise), use descriptive
messages for these commits, and ensure you are regularly pushing your code back to GitHub.

# Marking
The assessment has a total of 335 marks available across the following criteria:

## Technical Implementation - 235 marks (~70%)

Each exercise has a set number of marks available. You will be marked on the following:
* Solution successfully compiles
* Adherence to the task requirements
* Correct usage of programming techniques 
* Efficiency of the code
* Implementation of advanced requirements (where relevant)
* Correct use of coding conventions (e.g. formatting, indentation, commenting)
In addition to the marks are also available for:

## Repository Presentation - 35 marks (~10%)
Have you saved your exercises to the correct location and made appropriate use of commits (e.g. per task
with descriptive messages)

## Extended Learning - 65 marks (~20%)
Independent study is a crucial element of university study and helps solidify and extend learning. Additional
marks are available for the completion of the following online course:

[Introduction to Python](https://www.sololearn.com/en/learn/courses/python-introduction)




## Exercise 1: Coding is Cool- 10 Marks

Fill in the blanks in the Python code below to output the phrase **"Coding is Cool"** to the console using variables and string concatenation.


### Fill in the blanks below
```python
word1 = 
word2 = 
word3 =

# Use string concatenation to combine the variables and print the phrase
_____(_________)

```

__________________________________________________________________________________

## Exercise 2: Simple Sums - 15 Marks

In this exercise, you will create and work with integer variables, perform arithmetic operations, and print the result to the console.

### Steps:
1. Declare a variable and initialize it with the integer value `8`.
2. Declare a second variable and initialize it with the integer value `10`.
3. Declare a third variable that stores the sum of first two numbers.
4. Print the value of the sum to the console.

__________________________________________________________________________________

## Exercise 3: Biography - 25 Marks

In this exercise, you'll create a program that stores and prints your name, hometown, and age to the console using a Python dictionary.

### Steps:
1. Store the information (name, hometown, and age) as key-value pairs in a dictionary.
2. Print the values on separate lines using a single `print()` statement.
3. Use variables with appropriate data types for each piece of information.



### Advanced Requirements:
Have the user input their name, hometown, and age instead of hardcoding the values.
Try giving both your first and second name when asked for your name. What happens? How can you handle multiple words in Python?
Test the program by entering a string value for age (e.g., "twenty"). What happens? How can you prevent this issue?


__________________________________________________________________________________


## Exercise 4: Primitive Quiz - 30 Marks

In this exercise, you'll create a simple program that asks the user a question, evaluates their answer, and provides feedback.

### Steps:
1. Write a program that asks the user "What is the capital of France?" and waits for their response.
2. If the user's answer is correct (i.e., "Paris"), the program should print a message saying the answer is correct.
3. If the answer is incorrect, the program should print a message saying the answer is wrong.

### Advanced Requirements:
Ignore Capitalization: Modify your program to accept answers regardless of the capitalization (e.g., "paris", "Paris", and "PaRis" should all be considered correct).
Multiple Questions: Extend the program into a quiz that asks for the capitals of 10 European countries. Provide feedback for each question.

___________________________________________________________________________________

## Exercise 5: Days of the Month - 30 Marks

Write a program that tells a user how many days there are in a specific month. Use a dictionary to map the month numbers (1-12) to the number of days in each month.

### Instructions:
1. Create a Dictionary: Define a dictionary where the keys are month numbers and the values are the number of days in those months.
2. Input Handling: Ask the user to input the month number.
3. Check and Output: Use an if-else statement to check if the input is valid and print the number of days in the corresponding month.

### Advanced Requirement:
Leap Year Adjustment: Modify the program to account for leap years. For February, ask the user if the year is a leap year and adjust the number of days accordingly.


____________________________________________________________________________________

## Exercise 6: Brute Force Attack - 30 Marks

Write a program that simulates a password entry system. The correct password is defined as 12345. The program should keep asking the user to enter the password until they provide the correct one.

### Basic Requirements:
1. Define the correct password.
2. Use a while loop to repeatedly ask the user for the password until the correct one is entered.
3. Output an appropriate message when the correct password is entered.

### Optional Requirements:

Modify the program to include a maximum of 5 password attempts. If the user enters the wrong password, inform them of the remaining attempts. If the maximum number of attempts is reached, inform the user that the authorities have been alerted.


_____________________________________________________________________________________

## Exercise 7: Some Counting - 20 Marks

Use your newly acquired knowledge of the for loop to complete the following tasks. Print all values to the console
in each case.
* Write a loop that counts up from 0 to 50 in increments of 1.
* Write a loop that counts down from 50 to 0 in decrements of 1.
* Write a loop that counts up from 30 to 50 in increments of 1.
* Write a loop that counts down from 50 to 10 in decrements of 2.
* Write a loop that counts up from 100 to 200 in increments of 5.
*You may include all loops in a single project*


______________________________________________________________________________________


## Exercise 8: Simple Search - 30 Marks

Write a program that searches for a specific string within a list of strings. The list is initialized with specific names ("Jake" "Zac", "Ian", "Ron", "Sam", "Dave"). , and your task is to search for "Sam".

### Optional Requirements:
1. Allow the user to input the search term instead of using a predefined value.
2. Implement the search functionality based on user input.

_______________________________________________________________________________________


## Exercise 9: Hello - 10 Marks

Fill in the blanks in the code below so that the function hello() prints "Hello" to the console.
```python

def hello():
    ____  # Fill in this blank to print "Hello" to the console

def main():
    ____  # Fill in this blank to call the hello() function

if __name__ == "__main__":
    main()
```
________________________________________________________________________________________

## Exercise 10: Is it even? - 35 Marks

Write a program that tests if a value is even or odd. Follow the instructions outlined below:

### Instructions:
* The program should ask the user for a number from within the main function.
* The entered number should be passed to a function that determines if the value is even or odd.
* The function should return a message indicating whether the number is even or odd.
* The message returned by the function should be printed from within the main function.


_________________________________________________________________________________________

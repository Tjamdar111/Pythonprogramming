# Pythonprogramming
## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
--> As python programming language designed to be used for building software in a wide variety of application domains including data science, software and web development, automation, and generally getting stuff done across a multitude of hardware configurations.Thus it's called general purpose language.
When compiled, other languages turn into Assembly and run directly in the processor. As python being an interpreted language, which is not subject to the processor, makes Python a high-level programming language. Also, Python is a high-level programming language that is known for its ease of readability and  because its syntax so closely resembles the English language. 

Q2. Why is Python called a dynamically typed language?
-->Python is a dynamically typed language. As the Python interpreter does type checking only as code runs, and the type of a variable is allowed to change over its lifetime.

Q3. List some pros and cons of Python programming language?
--> Pros of python programming language.
    Python is easy to learn and read
    Python enhances productivity
    Python has a vast collection of libraries
    Python is free, open-source, and has a vibrant community
    Python is a portable programming language
    Python is an interpreted language
    It's Highly Compatible.
    It is Object-Oriented.
    It has Built-in Data Structures.
    It's Widely Applicable.

    Cons of python programming.
    Python has speed limitations
    Python is not so strong with mobile computing
    Python can have runtime errors
    Python consumes a lot of memory space
    Python is not easy to test


Q4. In what all domains can we use Python?
--> Python is the go-to programming language for domains such as artificial intelligence, machine learning and deep learning, it's no surprise that it's also a fundamental tool for any data scientist.Python can also use for web development, OS development,Scientific programming, Gaming etc.

Q5. What are variable and how can we declare them?
--> A variable in python is a symbolic name that is a reference or pointer to an object. Once an object is assigned to a variable, you can refer to the object by that name.Python has no command for declaring a variable. A variable is created the moment you first assign a value to it.In terms we can say that a variable is a name given to a memory location.

Q6. How can we take an input from the user in Python?
--> We can use input function(input()) to a input from the user in python but input function automatically converts the user input into string. We need to explicitly convert the input using the type casting.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
--> String is the default datatype of the value that has been taken as an input using input() function.

Q8. What is type casting?
--> Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.
There can be two types of Type Casting in Python –

Implicit Type Casting
Explicit Type Casting

 Python converts data type into another data type automatically. In this process, users don’t have to involve in this process is called implicit type casting.

In this method, Python need user involvement to convert the variable data type into certain data type in order to the operation required.


Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
--> No, We can take only one input from the user using single input() function. If we pass two arugement in a single input function we will get an error.

Q10. What are keywords?
--> Keywords in Python are unique reserved words that cannot use a keyword as a variable, function, or other identifiers. These special words are used to define the syntax and structure of the Python language.

Q11. Can we use keywords as a variable? Support your answer with reason.
--> No, we can't use keywords as variable as keywords are specially reserved words that cannot use as a variable.

Q12. What is indentation? What's the use of indentaion in Python?
--> Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important. Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
--> The basic way to throw an output in python is a print function.

Q14. What are operators in Python?
-->In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands.
Different types of operators: arithmetic operators, assignment operators, comparison operators, logical operators, identity operators, membership operators, and boolean operators

Q15. What is difference between / and // operators?
--> The difference between float division and integer or floor division is that while we use float division we will a value in float and in floor division the division of operands where the result is the quotient in which the digits after the decimal point are removed (integer). But if one of the operands is negative, the result is floored , i.e., rounded away from zero (towards negative infinity).

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
--> a = "ineuron"
print(a*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
-->  # User input
a = int(input("enter the value"))

# The number should be positive value or ask user to enter the positive value.
if a>0:
    if a%2 == 0:
        print(a ," is a even number")
    
    else:
        print (a," is a odd number")
else:
    print("enter positive value")

            

Q18. What are boolean operator?
-->Boolean Operators are those that result in the Boolean values of True and False. These include and, or and not. While and & or require 2 operands, not is a unary operator. Boolean operators are most commonly used in arithmetic computations and logical comparisons.Expressions that yield these Boolean values and are formed with operators called Boolean operators are called Boolean expressions. The operations that take place in the process are called Boolean operations.

Q19. What will the output of the following?
-->```
1 or 0 --> 1

0 and 0 --> 0

True and False and True --> False

1 or 0 or 0 --> 1
```

Q20. What are conditional statements in Python?
-->Conditonal Statement is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program.

Python has 3 key Conditional Statements that you should know:

if statement
if-else statement
if-elif-else ladder

Q21. What is use of 'if', 'elif' and 'else' keywords?
--> It allows us to check for multiple expressions. If the condition for if is False , it checks the condition of the next elif block and so on. If all the conditions are False , the body of else is executed. 

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
--> # Taking input from the user.
 
age = int(input("enter your age = " ))

if age>0:
    if age >18:
        print(" You can vote")
    else:
        print("You cannot vote")
else:
    print("value should be positive ")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
-->
numbers = [12, 75, 150, 180, 145, 525, 50] 
sum =0
for i in numbers:
    if i % 2 == 0:
        sum = sum+i
    else:
        continue
  
print(sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
-->num1 = int(input(" Enter the value"))
num2 = int(input(" Enter the value"))
num3 = int(input(" Enter the value"))

a = []
a.append(num1)
a.append(num2)
a.append(num3)

if a[0] > a[1] and a[0] > a[2]:
    print(a[0])

elif a[1]>a[2]:
    print(a[1])
else:
    print(a[2])


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five
- If the number is greater than 150, then skip it and move to the next number
- If the number is greater than 500, then stop the loop
numbers = [12, 75, 150, 180, 145, 525, 50]
-->
for i in numbers:
    if i%5 == 0:
        if i > 150:
            continue
        if i > 500:
            break
        print(i)

## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Ans. Python is called a general-purpose programming language because it can be used to develop a wide range of software, including web applications, desktop applications, scientific applications, and more. It has a large standard library that includes modules for many different tasks, making it easy for developers to accomplish a wide range of tasks without having to write their own code from scratch.

It is also called a high-level programming language because it provides a higher level of abstraction from the underlying hardware and system than low-level programming languages like Assembly or C. This makes it easier for developers to understand and use, as they can focus on solving problems and writing code at a higher level, rather than dealing with complex and often tedious low-level details.

Q2. Why is Python called a dynamically typed language?

Ans. Some languages, such as C++ and Java, need to know what type every variable is when it’s compiled. So if we say “x = 5”, we have to specify if x is an integer, a float, or something else. If we don’t, our code won’t even compile.

Dynamically typed languages such as python will figure out the type during runtime. This means that if you tell it “x = 5” it’ll go “Okay! Hmm, this looks like an integer…” and create an integer with the value 5 stored on it. It’ll do that for you automatically. It’ll even update the value to a float if you add a non-whole number to it, like so:
x = 5 
print(type(x))  # prints: <class 'int'> 
 
x = x + 0.5 
print(type(x))  # prints: <class 'float'> 

Q3. List some pros and cons of Python programming language?

Ans. 
Pros:
1.Simple and easy-to-understand syntax.
2.Object Oriented Programming-driven.
3.Supports imperative and functional programming.
4.Extensive library.
5.Supports multiple platforms (Web and mobile computing).
6.Python is easily extensible with C/C++/Java code.
7.Open Source and large community support.

Cons:
1.Python is slow.
2.Weak in mobile computing.
3.Has limitations with database access.
4.Despite being open source, there is no commercial support point.
5.Since Python is dynamic, more errors show at run-time.

Q4. In what all domains can we use Python?

Ans. Python can be used in a variety of domains due to its versatility and ease of use. Some of the most common domains where Python is used are:

1.Web Development
2.Scientific Computing
3.Artificial Intelligence and Machine Learning
4.Desktop Applications
5.Networking
6.Game Development
7.Automation and Scripting
8.Financial Services

Q5. What are variable and how can we declare them?

Ans: A variable is a named storage location in a computer's memory that can hold a value. Variables allow us to store data in a program so that we can use it later, or pass it between different parts of the program.
In Python, we can declare a variable by assigning a value to it. For example: 
x = 42
we can also change its value later in the program by simply reassigning it a new value:
x = 43
In Python, we do not need to specify the data type of a variable when we declare it, as the type is determined dynamically based on the value we assign to it.

Q6. How can we take an input from the user in Python?

Ans. We can take input from the user by using the input() function.
Ex: 
name = input("What is your name? ")
print("Hello, " + name + "!")


Q7. What is the default datatype of the value that has been taken as an input using input() function?

Ans.The default data type of the value that is taken as an input using the input() function is always a string.
ex. name = input("Enter your name: ")
print("Your name is:", type(name))
This code will always print "Your name is: <class 'str'>" because the input() function returns a string.

Q8. What is type casting?

Ans.Type casting, also known as type conversion, is the process of converting a value from one data type to another data type. In programming, type casting is often necessary when working with data of different types, such as converting a string to an integer or a floating-point number to a string.

In Python, we can perform type casting using functions such as int(), float(), str(), list(), tuple(), and dict(). For example:
x = "42"
y = int(x)  # Convert the string x to an integer

a = 42
b = str(a)  # Convert the integer a to a string

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Ans.No, we cannot take more than one input from the user using a single input() function in Python. The input() function can only be used to read a single line of text from the standard input (usually the keyboard).
If we need to take multiple inputs from the user, we can call the input() function multiple times, one for each input we need to read. 
For example:
name = input("Enter your name: ")
age = int(input("Enter your age: "))

Q10. What are keywords?

Ans.In programming, keywords are reserved words that have a special meaning in a programming language. They cannot be used as variable names or any other identifier.

In Python, keywords are used to define the structure and syntax of the language. There are 35 keywords in Python 3:
and       as        assert    async    await
break     class     continue  def      del
elif      else      except    False    finally
for       from      global    if       import
in        is        lambda    None     nonlocal
not       or        pass      raise    return
True      try       while     with     yield


Q11. Can we use keywords as a variable? Support your answer with reason.

Ans.No, we cannot use keywords as variables in Python. Keywords are reserved words that have a special meaning in the language, and they cannot be used as identifiers.

Using keywords as variables can cause confusion and lead to syntax errors, since the keywords have a specific meaning in the language and are used to define the structure and syntax of the code.
ex. for = 42  # Raises a SyntaxError exception


Q12. What is indentation? What's the use of indentaion in Python?

Ans. Indentation refers to the spaces at the beginning of a code line. In Python, indentation is used to indicate a block of code. It helps to define the structure of the code and delimit the blocks of code that belong together, such as loops, functions, and classes. Indentation is a visual way of defining the scope of these blocks and helps improve the readability of the code. In Python, the standard indentation is 4 spaces.

Q13. How can we throw some output in Python?

Ans.We can output text in Python using the "print()" function.
ex. print("Hello, World!")
This will output: Hello, World!



Q14. What are operators in Python?

Ans.In Python, operators are symbols that perform operations on values
Some of the common operators in Python are:
Arithmetic operators: + (addition), - (subtraction), * (multiplication), / (division), % (modulus), // (floor division), and ** (exponentiation)

Comparison operators: == (equal to), != (not equal to), > (greater than), < (less than), >= (greater than or equal to), and <= (less than or equal to)

Assignment operators: = (assign), += (add and assign), -= (subtract and assign), *= (multiply and assign), /= (divide and assign), %= (modulus and assign), and **= (exponentiation and assign)

Logical operators: and, or, not

Bitwise operators: & (and), | (or), ^ (xor), ~ (not), << (left shift), and >> (right shift)

The results of operations performed by operators can be used for making decisions, calculating values, and performing other operations.

Q15. What is difference between / and // operators?

Ans. In Python, "/" (division) and "//" (floor division) are two different types of division operators.
 the "/" operator returns a floating-point number, while the "//" operator returns an integer.
ex.
print(10 / 3) # Out put will be 3.3333333333333335

    print(10 // 3)  # Out put will be 3

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

Ans. 

print("iNeuron" * 4)


Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Ans. 
num = int(input("Enter a number: "))

if num % 2 == 0:

    print(num, "is even.")
    
else:

    print(num, "is odd.")


Q18. What are boolean operator?

Ans.Boolean operators are logical operators that allow us to manipulate and compare values in a binary system (i.e. true/false, 1/0). There are three main Boolean operators:

1.AND (&& or &): returns true if both operands are true, and false otherwise.

2.OR (|| or |): returns true if either one of the operands is true, and false otherwise.

3.NOT (!): returns the opposite of the operand. If the operand is true, NOT returns false, and if the operand is false, NOT returns true.

These operators are used in many programming languages, including C, C++, Java, and Python, to perform conditional tests and control the flow of execution.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Ans.1 or 0
the expression returns 1 (or True).

0 and 0
the expression returns 0 (or False).

True and False and True
expression returns False.

1 or 0 or 0
the expression returns 1 (or True)

Q20. What are conditional statements in Python?

Ans. Conditional statements in Python allow us to control the flow of execution based on whether certain conditions are met. The most common conditional statements in Python are if statements and if-else statements.
ex.
x = 5

if x > 0:
    print("x is positive")
else:
    print("x is non-positive")


Q21. What is use of 'if', 'elif' and 'else' keywords?

Ans.The if, elif, and else keywords are used in Python to control the flow of execution based on conditions.

if: The if keyword is used to specify a block of code that should be executed only if a certain condition is met. 
The syntax for an if statement is: 
if condition:
    # code to be executed if condition is True

If the condition evaluates to True, the code indented under the if statement is executed. If the condition evaluates to False, the code under the if statement is skipped.

elif: The elif keyword is used in conjunction with an if statement to specify additional conditions to be tested if the previous conditions in the if and elif statements are not met. 
The syntax for an elif statement is:
if condition_1:
    # code to be executed if condition_1 is True
elif condition_2:
    # code to be executed if condition_1 is False and condition_2 is True

We can use multiple elif statements to specify multiple conditions to be tested. If any of the conditions evaluate to True, the corresponding block of code is executed, and the rest of the conditions are skipped.

else: The else keyword is used in conjunction with an if statement to specify a block of code that should be executed if all of the conditions in the if and elif statements are not met. 
The syntax for an else statement is:
if condition_1:
    # code to be executed if condition_1 is True
elif condition_2:
    # code to be executed if condition_1 is False and condition_2 is True
else:
    # code to be executed if condition_1 and condition_2 are False
The else statement provides a catch-all clause that will be executed if none of the conditions in the if and elif statements are met.


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Ans.
age = int(input("Enter your age: "))

if age >= 18:
    print("I can vote")
else:
    print("I can't vote")


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans.
numbers = [12, 75, 150, 180, 145, 525, 50]

def even_sum(numbers):
    even_sum = 0
    for number in numbers:
        if number % 2 == 0:
            even_sum += number
    return even_sum

result = even_sum(numbers)
print("The sum of all even numbers is:", result)



Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Ans. 
def find_greatest_number(num1, num2, num3):
    greatest = num1
    if num2 > greatest:
        greatest = num2
    if num3 > greatest:
        greatest = num3

    print("The greatest number is: ", greatest)

num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
num3 = int(input("Enter third number: "))

find_greatest_number(num1, num2, num3)


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans.
numbers = [12, 75, 150, 180, 145, 525, 50]

for num in numbers:
    if num > 150:
        continue
    if num % 5 == 0:
        if num > 500:
            break
        print(num)

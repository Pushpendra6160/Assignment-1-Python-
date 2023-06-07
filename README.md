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
ex. 
print("Hello, World!")
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
        
 Q26. What is a string? How can we declare string in Python?
Ans In Python, a string is a sequence of characters enclosed within either single quotes ('') or double quotes (""). It is a data type used to represent textual data. Strings are immutable, meaning their values cannot be changed after they are created.
are a few examples:
str1 = 'Hello, World!'  # Single quotes
str2 = "Python Programming"  # Double quotes
str3 = '''This is a multi-line
string'''  # Triple quotes for multi-line strings 

Q27. How can we access the string using its index?
Ans.  In Python, you can access individual characters of a string using indexing. The indexing starts from 0 for the first character, and you can use positive or negative indices to access characters from the beginning or end of the string, respectively.
Here's an example:
string = "Hello, World!"
print(string[0])    # Output: 'H' (first character)
print(string[7])    # Output: 'W' (eighth character)
print(string[-1])   # Output: '!' (last character)
print(string[-6])   # Output: ' ' (space character)

Q28. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "iNeuron"
Ans. 
string = "Big Data iNeuron"
desired_output = string[8:]  # Extracts the substring from index 8 till the end
print(desired_output)  # Output: "iNeuron"

Q29. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "norueNi"

Q30. Resverse the string given in the above question.
Ans. To reverse the string, you can use string slicing with a step value of -1. Here's the code:
string = "Big Data iNeuron"
reversed_string = string[::-1]  # Slicing with step -1 to reverse the string
print(reversed_string)  # Output: "norueNi ataD giB"



Q31. How can you delete entire string at once?
Ans.  In Python, strings are immutable, which means you cannot delete or modify a string directly. However, you can delete a string variable using the del keyword. Once deleted, the memory occupied by the string will be freed.

Here's an example:

string = "Hello, World!"
del string
# Now, the string variable no longer exists

Q32. What is escape sequence?
Ans. An escape sequence is a combination of characters used to represent certain characters that are difficult to type or are reserved in a string literal. Escape sequences are represented by a backslash () followed by a specific character or code.

Some common escape sequences in Python are:

'\': Single quote
"\": Double quote
'\\': Backslash
'\n': New

Q33. How can you print the below string?

'iNeuron's Big Data Course'
Ans. 
print("iNeuron's Big Data Course")
# Output: iNeuron's Big Data Course

print('iNeuron\'s Big Data Course')
# Output: iNeuron's Big Data Course

Q34. What is a list in Python?
Ans.In Python, a list is an ordered collection of items enclosed in square brackets ([]). It is a mutable data type, meaning you can modify the elements of a list after it is created. A list can contain elements of different data types, such as integers, strings, floats, or even other lists. Lists are one of the most commonly used data structures in Python.

Q35. How can you create a list in Python?
Ans.To create a list in Python, you can enclose a comma-separated sequence of elements inside square brackets ([]). Here are a few examples:

empty_list = []  # Empty list

numbers = [1, 2, 3, 4, 5]  # List of integers

fruits = ['apple', 'banana', 'orange']  # List of strings

mixed = [10, 'hello', 3.14, True]  # List with elements of different types

nested = [[1, 2], ['a', 'b', 'c']]  # List containing other lists

Q36. How can we access the elements in a list?
Ans. In Python, you can access individual elements of a list using indexing. List indexing starts from 0 for the first element, and you can use positive or negative indices to access elements from the beginning or end of the list, respectively.

Here's an example:

numbers = [1, 2, 3, 4, 5]

print(numbers[0])    # Output: 1 (first element)
print(numbers[2])    # Output: 3 (third element)
print(numbers[-1])   # Output: 5 (last element)
print(numbers[-3])   # Output: 3 (third element from the end)

Q37. Write a code to access the word "iNeuron" from the given list.

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
Ans.Here's the code to access the word "iNeuron" from the given list:

lst = [1, 2, 3, "Hi", [45, 54, "iNeuron"], "Big Data"]
word = lst[4][2]  # Accessing the word "iNeuron" using nested indexing
print(word)  # Output: iNeuron

Q38. Take a list as an input from the user and find the length of the list.
Ans.
lst = input("Enter elements of the list (comma-separated): ").split(",")
length = len(lst)
print("Length of the list:", length)


Q39. Add the word "Big" in the 3rd index of the given list.

lst = ["Welcome", "to", "Data", "course"]
Ans. 
lst = ["Welcome", "to", "Data", "course"]
lst.insert(3, "Big")
print(lst)
# Output: ["Welcome", "to", "Data", "Big", "course"]


Q40. What is a tuple? How is it different from list?
Ans.In Python, a tuple is an ordered collection of elements enclosed in parentheses (). It is similar to a list, but the main difference is that tuples are immutable, meaning their elements cannot be modified once they are assigned. Tuples are commonly used to store related pieces of information together.

The main differences between a tuple and a list are:

Tuples are immutable, whereas lists are mutable.
Tuples are typically used to store heterogeneous data (elements of different types), while lists can store elements of any type.
Tuples use parentheses () for declaration, while lists use square brackets [].

Q41. How can you create a tuple in Python?
Ans.To create a tuple in Python, you can enclose a comma-separated sequence of elements inside parentheses (). 
Here are a few examples:

empty_tuple = ()  # Empty tuple

single_value_tuple = (10,)  # Tuple with a single element

mixed_tuple = (10, 'hello', 3.14, True)  # Tuple with elements of different types

nested_tuple = ((1, 2), ('a', 'b', 'c'))  # Tuple containing other tuples


Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
Ans.No, We cannot directly add an element to an existing tuple because tuples are immutable. Once a tuple is created, we cannot modify its elements. If we try to use the append() or insert() method on a tuple, it will result in an error.

tuple1 = ("apple", "banana", "cherry")
tuple1.append("orange")  # Error: 'tuple' object has no attribute 'append'

To add elements to a tuple, you need to create a new tuple with the desired elements.

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
Ans.  No, two tuples cannot be appended directly because tuples are immutable, and their elements cannot be modified. However, you can concatenate two tuples to create a new tuple that contains elements from both tuples.

Here's an example of concatenating two tuples:

tuple1 = (1, 2, 3)
tuple2 = (4, 5, 6)
concatenated_tuple = tuple1 + tuple2
print(concatenated_tuple)
# Output: (1, 2, 3, 4, 5, 6)

Q44. Take a tuple as an input and print the count of elements in it.
Ans. Here's the code to take a tuple as input and print the count of elements in it:

tuple1 = tuple(input("Enter elements of the tuple (comma-separated): ").split(","))
count = len(tuple1)
print("Count of elements:", count)

Q45. What are sets in Python?
Ans.  In Python, a set is an unordered collection of unique elements. It is a built-in data type that is used to store multiple items in a single variable. Sets are defined by enclosing a comma-separated sequence of elements inside curly braces {} or by using the set() constructor.

Sets are commonly used to perform mathematical set operations such as union, intersection, and difference. They provide methods to add, remove, and perform various operations on elements.

Q46. How can you create a set?
Ans.There are two ways to create a set in Python:

Using curly braces {}:

set1 = {1, 2, 3, 4, 5}

Using the set() constructor:

set2 = set([1, 2, 3, 4, 5])

In both cases, we define a sequence of elements separated by commas inside the braces or passed as an argument to the set() constructor.


Q47. Create a set and add "iNeuron" in your set.
Ans.
my_set = {"Python", "Data Science", "Machine Learning"}
my_set.add("iNeuron")
print(my_set)


Q48. Try to add multiple values using add() function.
Ans.The add() function in sets is used to add a single element to the set. If you want to add multiple values to a set, you can use the update() function or directly provide multiple values when creating the set.

Using the update() function:

my_set = {"Python", "Data Science"}
my_set.update(["Machine Learning", "Deep Learning"])
print(my_set)

Output:
{'Python', 'Data Science', 'Machine Learning', 'Deep Learning'}

Q49. How is update() different from add()?
Ans.The add() method in sets is used to add a single element to the set, whereas the update() method is used to add multiple elements to the set. The update() method takes an iterable as an argument and adds all the elements from that iterable to the set.

Here's an example to illustrate the difference:

my_set = {"Apple", "Banana"}
my_set.add("Orange")
print(my_set)
# Output: {'Banana', 'Orange', 'Apple'}

my_set.update(["Mango", "Pineapple"])
print(my_set)
# Output: {'Banana', 'Orange', 'Mango', 'Pineapple', 'Apple'}

Q50. What is clear() in sets?
Ans.In Python sets, the clear() method is used to remove all elements from a set, making it an empty set. It modifies the set in place and does not return any value.

Here's an example:

my_set = {1, 2, 3, 4, 5}
print(my_set)
# Output: {1, 2, 3, 4, 5}

my_set.clear()
print(my_set)
# Output: set()

Q51. What is frozen set?
Ans.In Python, a frozen set is an immutable version of a set. It is an unordered collection of unique elements, just like a regular set, but once a frozen set is created, its elements cannot be changed or modified. Frozen sets are useful when you need to create a set that is guaranteed to remain unchanged.

Frozen sets can be created by using the frozenset() function with an iterable as an argument. 
Here's an example:

my_frozen_set = frozenset([1, 2, 3, 4, 5])

Once a frozen set is created, we cannot add or remove elements from it.

Q52. How is frozen set different from set?
Ans.The main difference between a frozen set and a regular set in Python is that a frozen set is immutable, meaning its elements cannot be changed once it is created, while a regular set is mutable and allows modifications to its elements.

Here are some key differences:

Mutability: A regular set is mutable, which means you can add or remove elements from it using methods like add(), remove(), or discard(). On the other hand, a frozen set is immutable, so you cannot modify its elements after creation.

Hashability: Frozen sets are hashable and can be used as elements of other sets or as keys in dictionaries, while regular sets are not hashable because they are mutable.

Usage: Regular sets are commonly used when you need to store a collection of unique and mutable elements, while frozen sets are used when you want to create an immutable set that won't be modified.

Q53. What is union() in sets? Explain via code.
Ans. In sets, the union() method is used to return a new set that contains all the unique elements from two or more sets. It performs the union operation, which combines the elements from multiple sets without any duplicates.

Here's an example to explain the union() method:

set1 = {1, 2, 3}
set2 = {3, 4, 5}
set3 = {5, 6, 7}

union_set = set1.union(set2, set3)
print(union_set)

Output:
{1, 2, 3, 4, 5, 6, 7}

Q54. What is intersection() in sets? Explain via code.
Ans.In sets, the intersection() method is used to return a new set that contains the common elements between two or more sets. It performs the intersection operation, which finds the elements that exist in all the sets.

Here's an example to explain the intersection() method:

set1 = {1, 2, 3, 4}
set2 = {3, 4, 5}
set3 = {4, 5, 6}

intersection_set = set1.intersection(set2, set3)
print(intersection_set)

Output:
{4}

Q55. What is dictionary ibn Python?
Ans. A dictionary in Python is a built-in data structure that stores a collection of key-value pairs. It is used to map keys to corresponding values, allowing efficient retrieval of values based on their associated keys. Dictionaries are mutable, unordered, and indexed by keys. Each key in a dictionary must be unique and can be of any immutable type, while the corresponding values can be of any type.


Q56. How is dictionary different from all other data structures.
Ans.Dictionaries differ from other data structures in Python in the following ways:

Lists and tuples are ordered collections of elements, while dictionaries are unordered.
Dictionaries use key-value pairs to store and access data, while lists and tuples use indexing to access elements.
Dictionaries are mutable, meaning their contents can be modified after creation, while tuples are immutable and lists are mutable.
Dictionaries provide efficient lookup and retrieval of values based on their keys, using a hash table implementation.

Q57. How can we delare a dictionary in Python?
Ans.There are several ways to declare a dictionary in Python. Here are a few examples:

Using curly braces {} and separating key-value pairs with colons:

my_dict = {'key1': 'value1', 'key2': 'value2', 'key3': 'value3'}
Using the dict() function:

my_dict = dict(key1='value1', key2='value2', key3='value3')
Using a combination of lists for keys and values:

keys = ['key1', 'key2', 'key3']
values = ['value1', 'value2', 'value3']
my_dict = dict(zip(keys, values))

Q58. What will the output of the following?

var = {}
print(type(var))
Ans.The output of the following code will be:

<class 'dict'>

Q59. How can we add an element in a dictionary?
Ans.To add an element to a dictionary in Python, we can assign a value to a new key or an existing key using the assignment operator (=). Here's an example:

my_dict = {'key1': 'value1', 'key2': 'value2'}
my_dict['key3'] = 'value3'  # Adding a new key-value pair
my_dict['key2'] = 'new value'  # Modifying the value of an existing key

After executing the above code, the dictionary my_dict will have three key-value pairs:

{
  'key1': 'value1',
  'key2': 'new value',
  'key3': 'value3'
}

Q60. Create a dictionary and access all the values in that dictionary.
Ans. To create a dictionary and access all the values, you can follow this example:

my_dict = {'key1': 'value1', 'key2': 'value2', 'key3': 'value3'}

# Accessing all the values in the dictionary
values = my_dict.values()

# Printing all the values
for value in values:
    print(value)

Q61. Create a nested dictionary and access all the element in the inner dictionary.
Ans.To create a nested dictionary and access all the elements in the inner dictionary, you can use the following example:
my_dict = {
    'outer_key1': {'inner_key1': 'value1', 'inner_key2': 'value2'},
    'outer_key2': {'inner_key3': 'value3', 'inner_key4': 'value4'}
}
# Accessing all the elements in the inner dictionary
for outer_key, inner_dict in my_dict.items():
    for inner_key, value in inner_dict.items():
        print(f"Outer Key: {outer_key}, Inner Key: {inner_key}, Value: {value}")


Q62. What is the use of get() function?
Ans.The get() function in Python is used to retrieve the value associated with a given key in a dictionary. It takes the key as the argument and returns the corresponding value. The advantage of using get() is that if the key is not present in the dictionary, it returns a default value (which can be specified as the second argument to get()) instead of raising a KeyError exception.

Here's an example of using the get() function:

my_dict = {'key1': 'value1', 'key2': 'value2'}
value = my_dict.get('key1')
print(value)  # Output: 'value1'

value = my_dict.get('key3', 'default')
print(value)  # Output: 'default'

Q63. What is the use of items() function?
Ans.The items() function is used to return a list of all the key-value pairs in a dictionary. It returns a view object that contains tuples of the form (key, value). This function is often used when you need to iterate over both the keys and values of a dictionary simultaneously.

Here's an example of using the items() function:
my_dict = {'key1': 'value1', 'key2': 'value2'}

# Iterating over key-value pairs using items()
for key, value in my_dict.items():
    print(f"Key: {key}, Value: {value}")

Q64. What is the use of pop() function?
Ans.The pop() function in Python is used to remove and return the value associated with a specified key from a dictionary. It takes the key as an argument and returns the corresponding value. After removing the key-value pair from the dictionary, it is no longer accessible.

Here's an example of using the pop() function:

my_dict = {'key1': 'value1', 'key2': 'value2', 'key3': 'value3'}
value = my_dict.pop('key2')
print(value)  # Output: 'value2'
print(my_dict)  # Output: {'key1': 'value1', 'key3': 'value3'}

Q65. What is the use of popitems() function?
Ans. The popitem() function in Python is used to remove and return an arbitrary key-value pair from a dictionary. It is useful when you want to remove an element from the dictionary without specifying a particular key. The popitem() function removes the last added key-value pair in versions before Python 3.7, and starting from Python 3.7, it removes a random key-value pair.

Here's an example of using the popitem() function:

my_dict = {'key1': 'value1', 'key2': 'value2', 'key3': 'value3'}
item = my_dict.popitem()
print(item)  # Output: ('key3', 'value3')
print(my_dict)  # Output: {'key1': 'value1', 'key2': 'value2'}

Q66. What is the use of keys() function?
Ans. The keys() function in Python is used to return a view object that contains all the keys present in a dictionary. The view object behaves like a set, providing various set operations like union, intersection, etc., that can be performed on the keys.

Here's an example of using the keys() function:

my_dict = {'key1': 'value1', 'key2': 'value2', 'key3': 'value3'}
keys = my_dict.keys()
print(keys)  # Output: dict_keys(['key1', 'key2', 'key3'])

Q67. What is the use of values() function?
Ans. The values() function in Python is used to return a view object that contains all the values present in a dictionary. Similar to the keys() function, the view object provided by values() behaves like a set and supports set operations.

Here's an example of using the values() function:

my_dict = {'key1': 'value1', 'key2': 'value2', 'key3': 'value3'}
values = my_dict.values()
print(values)  # Output: dict_values(['value1', 'value2', 'value3'])

Q68. What are loops in Python?
Ans.Loops in Python are control flow structures that allow repetitive execution of a block of code. They help automate repetitive tasks by iterating over a sequence or conditionally executing code until a certain condition is met. Loops enable efficient and concise coding by reducing redundancy.

Q69. How many type of loop are there in Python?
Ans. There are two types of loops in Python:

for loop: The for loop is used for iterating over a sequence (such as a list, tuple, string, or range) or any iterable object. It executes a block of code for each element in the sequence. The number of iterations is predetermined based on the length of the sequence or iterable.

while loop: The while loop repeatedly executes a block of code as long as a given condition is true. It checks the condition before each iteration and continues until the condition becomes false. The number of iterations is not predetermined and depends on the condition being evaluated.

Q70. What is the difference between for and while loops?
Ans. The main differences between for and while loops are as follows:

for loops are used when you know the number of iterations in advance (e.g., when iterating over a sequence), while while loops are used when the number of iterations is not known in advance and depends on a condition.
for loops iterate over a sequence or iterable, whereas while loops repeatedly execute code as long as a condition is true.
for loops handle iteration automatically, whereas while loops require explicit initialization, condition checking, and updating of variables within the loop.
for loops are generally used for iterating over known data, while while loops are often used when the termination condition depends on changing values during execution.

Q71. What is the use of continue statement?
Ans. The continue statement in Python is used to skip the rest of the current iteration of a loop and move to the next iteration. When the continue statement is encountered within a loop, the remaining code in that iteration is skipped, and the loop immediately starts the next iteration.

The main use of the continue statement is to selectively skip certain iterations based on specific conditions, allowing you to exclude certain elements or values from processing within a loop.

Here's an example to demonstrate the use of continue:

numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for num in numbers:
    if num % 2 == 0:
        continue  # Skip even numbers
    print(num)

Q72. What is the use of break statement?
Ans. The break statement in Python is used to terminate the execution of a loop prematurely. When the break statement is encountered within a loop, the loop is immediately exited, and the program continues with the next statement following the loop.

The primary use of the break statement is to exit a loop early based on certain conditions, allowing you to stop further iterations when a specific condition is met.

Here's an example to illustrate the use of break:

numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for num in numbers:
    if num == 6:
        break  # Exit the loop when 6 is encountered
    print(num)

Q73. What is the use of pass statement?
Ans. The pass statement in Python is a placeholder statement that does nothing. It is used when a statement is syntactically required but you don't want to execute any code. The pass statement acts as a null operation, allowing you to have a valid empty block of code.

The primary use of the pass statement is when you are designing the structure of your code or defining a function or class and want to leave the implementation details for later. It serves as a placeholder to prevent a syntax error in situations where an indented block is required.

Here's an example to demonstrate the use of pass:

def some_function():
    pass  # Placeholder for the function implementation

Q74. What is the use of range() function?
Ans. The range() function in Python is used to generate a sequence of numbers. It is commonly used in loops to control the number of iterations based on a specific range of values.

The range() function can take one, two, or three arguments:

With one argument: range(stop) generates a sequence from 0 to stop-1.
With two arguments: range(start, stop) generates a sequence from start to stop-1.
With three arguments: range(start, stop, step) generates a sequence from start to stop-1 with a specified step size.
Here are a few examples of using the range() function:

# Example 1: Generate numbers from 0 to 4
for num in range(5):
    print(num)  # Output: 0, 1, 2, 3, 4

# Example 2: Generate numbers from 1 to 5
for num in range(1, 6):
    print(num)  # Output: 1, 2, 3, 4, 5

# Example 3: Generate even numbers from 0 to 10
for num in range(0, 11, 2):
    print(num)  # Output: 0, 2, 4, 6, 8, 10

Q75. How can you loop over a dictionary?
Ans. To loop over a dictionary in Python, you can use the for loop along with the items() method of the dictionary. The items() method returns a view object that contains tuples of key-value pairs from the dictionary. By iterating over this view object, you can access both the keys and the corresponding values.

Q76. Write a Python program to find the factorial of a given number.
Ans. 
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

number = int(input("Enter a number: "))
factorial_value = factorial(number)
print("Factorial of", number, "is", factorial_value)


Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100
Ans. 
principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the interest rate: "))
time = float(input("Enter the time period (in years): "))

simple_interest = (principal * rate * time) / 100

print("Simple Interest:", simple_interest)


Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
Ans. 
principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the interest rate: "))
time = float(input("Enter the time period (in years): "))

compound_interest = principal * (pow((1 + rate / 100), time))

print("Compound Interest:", compound_interest)


Q79. Write a Python program to check if a number is prime or not.
Ans. 
def is_prime(n):
    if n <= 1:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True

number = int(input("Enter a number: "))
if is_prime(number):
    print(number, "is a prime number")
else:
    print(number, "is not a prime number")


Q80. Write a Python program to check Armstrong Number.
Ans.
def is_armstrong(n):
    num_str = str(n)
    num_digits = len(num_str)
    sum = 0
    for digit in num_str:
        sum += int(digit) ** num_digits
    if sum == n:
        return True
    else:
        return False

number = int(input("Enter a number: "))
if is_armstrong(number):
    print(number, "is an Armstrong number")
else:
    print(number, "is not an Armstrong number")




Q81. Write a Python program to find the n-th Fibonacci Number.
Ans.def fibonacci(n):
    if n <= 0:
        return "Invalid input. Please enter a positive integer."
    elif n == 1:
        return 0
    elif n == 2:
        return 1
    else:
        fib_minus_1 = 1
        fib_minus_2 = 0
        fib = 0
        for i in range(3, n+1):
            fib = fib_minus_1 + fib_minus_2
            fib_minus_2 = fib_minus_1
            fib_minus_1 = fib
        return fib

n = int(input("Enter the value of n: "))
result = fibonacci(n)
print("The", n, "th Fibonacci number is:", result)


Q82. Write a Python program to interchange the first and last element in a list.
Ans.
def interchange_first_last(lst):
    if len(lst) < 2:
        return "Invalid input. List should have at least two elements."
    lst[0], lst[-1] = lst[-1], lst[0]
    return lst

my_list = [1, 2, 3, 4, 5]
result = interchange_first_last(my_list)
print("List after interchanging first and last element:", result)


Q83. Write a Python program to swap two elements in a list.
Ans.
def swap_elements(lst, index1, index2):
    if 0 <= index1 < len(lst) and 0 <= index2 < len(lst):
        lst[index1], lst[index2] = lst[index2], lst[index1]
    return lst

my_list = [1, 2, 3, 4, 5]
index1 = 1
index2 = 3
result = swap_elements(my_list, index1, index2)
print("List after swapping elements:", result)



Q84. Write a Python program to find N largest element from a list.
Ans.
def find_n_largest_elements(lst, n):
    if n > len(lst):
        return "Invalid input. List contains fewer elements than N."
    sorted_list = sorted(lst, reverse=True)
    return sorted_list[:n]

my_list = [1, 10, 5, 20, 15, 30, 25]
N = 3
result = find_n_largest_elements(my_list, N)
print("The", N, "largest elements:", result)


Q85. Write a Python program to find cumulative sum of a list.
Ans.
def cumulative_sum(lst):
    cum_sum = 0
    result = []
    for num in lst:
        cum_sum += num
        result.append(cum_sum)
    return result

my_list = [1, 2, 3, 4, 5]
cumulative_sum_list = cumulative_sum(my_list)
print("Cumulative sum of the list:", cumulative_sum_list)


Q86. Write a Python program to check if a string is palindrome or not.
Ans.
def is_palindrome(string):
    reversed_string = string[::-1]
    if string == reversed_string:
        return True
    else:
        return False

my_string = input("Enter a string: ")
if is_palindrome(my_string):
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")


Q87. Write a Python program to remove i'th element from a string.
Ans.
def remove_character(string, index):
    if 0 <= index < len(string):
        new_string = string[:index] + string[index + 1:]
        return new_string
    else:
        return "Invalid index"

my_string = input("Enter a string: ")
i = int(input("Enter the index of the character to remove: "))
result = remove_character(my_string, i)
print("String after removing the character:", result)


Q88. Write a Python program to check if a substring is present in a given string.
Ans.
def is_substring_present(string, substring):
    if substring in string:
        return True
    else:
        return False

my_string = input("Enter a string: ")
my_substring = input("Enter a substring to search: ")
if is_substring_present(my_string, my_substring):
    print("Substring is present in the string.")
else:
    print("Substring is not present in the string.")


Q89. Write a Python program to find words which are greater than given length k.
Ans.
def find_words_greater_than_k(string, k):
    words = string.split()
    result = [word for word in words if len(word) > k]
    return result

my_string = input("Enter a string: ")
k = int(input("Enter the value of k: "))
greater_words = find_words_greater_than_k(my_string, k)
print("Words greater than length", k, "are:", greater_words)


Q90. Write a Python program to extract unquire dictionary values.
Ans.
def extract_unique_values(dictionary):
    unique_values = list(set(dictionary.values()))
    return unique_values

my_dict = {'a': 1, 'b': 2, 'c': 3, 'd': 2, 'e': 1}
unique_values = extract_unique_values(my_dict)
print("Unique values in the dictionary:", unique_values)


Q91. Write a Python program to merge two dictionary.
Ans.
def merge_dicts(dict1, dict2):
    merged_dict = {**dict1, **dict2}
    return merged_dict

dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}
merged_dict = merge_dicts(dict1, dict2)
print("Merged dictionary:", merged_dict)



Q92. Write a Python program to convert a list of tuples into dictionary.

Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
Ans.
def convert_to_dictionary(lst):
    dictionary = dict(lst)
    return dictionary

input_list = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
output_dict = convert_to_dictionary(input_list)
print("Output dictionary:", output_dict)

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
Ans.
def create_tuples_with_cube(lst):
    tuples_list = [(num, num ** 3) for num in lst]
    return tuples_list

input_list = [9, 5, 6]
output_tuples = create_tuples_with_cube(input_list)
print("Output list of tuples:", output_tuples)

Q94. Write a Python program to get all combinations of 2 tuples.

Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
Ans. 
from itertools import product

test_tuple1 = (7, 2)
test_tuple2 = (7, 8)

combinations = list(product(test_tuple1, test_tuple2))
print("All combinations of 2 tuples:", combinations)

Q95. Write a Python program to sort a list of tuples by second item.

Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
Ans.
def sort_list_of_tuples(lst):
    sorted_list = sorted(lst, key=lambda x: x[1])
    return sorted_list

input_list = [('for', 24), ('Geeks', 8), ('Geeks', 30)]
output_list = sort_list_of_tuples(input_list)
print("Sorted list of tuples:", output_list)

Q96. Write a python program to print below pattern.
Ans.
n = 5
for i in range(n):
    for j in range(i+1):
        print("*", end=" ")
    print()

Output:

* 
* * 
* * * 
* * * * 
* * * * *
Q97. Write a python program to print below pattern.

    *
   **
  ***
 ****
*****
Ans.
n = 5
for i in range(n):
    for j in range(n - i - 1):
        print(" ", end="")
    for k in range(i + 1):
        print("*", end="")
    print()

Q98. Write a python program to print below pattern.

    * 
   * * 
  * * * 
 * * * * 
* * * * * 
Ans.
n = 5
for i in range(n):
    for j in range(n - i - 1):
        print(" ", end="")
    for k in range(i + 1):
        print("*", end=" ")
    print()

Q99. Write a python program to print below pattern.

1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
Ans.
n = 5
for i in range(n):
    for j in range(i + 1):
        print(j + 1, end=" ")
    print()

Q100. Write a python program to print below pattern.

A 
B B 
C C C 
D D D D 
E E E E E 
Ans.
n = 5
for i in range(n):
    for j in range(i + 1):
        print(chr(i + 65), end=" ")
    print()

# Operations Using Data Type and Operators in Python

## Objective Domain 
- Data Type Conversion
- Input Output
- Dynamic Typing
- Number, Character, and String Transformation
- Python Check in String
- String Formatting
- List, Set, and String Operation
- Operator, Operands and Expression
- Conditional Expression

## Challange
- Requires a high understanding of the material
- Requires high accuracy to input data

## Expected Outcome
- Able to perform data and data type operations.
- Able to determine the sequence of execution based on operator precedence.
- Able to use operators to achive the intended results
-----
### Data Type Conversion
The process of converting the value of one data type (integer, string, float, etc.) to another data type is called type conversion. Python defines type conversion functions to directly convert one data type to another

### Input Output
For a program to be useful, it usually needs to communicate with the user by obtaining input data and displaying result data back to the user.

### Dynamic Typing
Python is a dynamically typed language. When declaring a variable in Python, you don’t specify a type for it, which means the Python interpreter does type checking only as code runs, and the type of a variable is allowed to change over its lifetime.


### Number, Character, and String Transformation
#### Case Manipulator
##### upper()
upper() is a built-in method used for string handling. The upper() methods returns the uppercased string from the given string. It converts all lowercase characters to uppercase. If no lowercase characters exist, it returns the original string.
##### lower()
ower() is a built-in method used for string handling. The lower() methods returns the lowercased string from the given string. It converts all uppercase characters to lowercase. If no uppercase characters exist, it returns the original string.
#### Prefix and Suffix
- rstrip() remove any white spaces at the end of the string
- lstrip() remove any white spaces to the left of string
- strip() Can specify which characters or sections you want to remove
#### Testing for Substring
- startswith(): The startwith() method will return True if the string starts with the word we want, otherwise it will return False.
- endswith(): The endswith() returns true if it ends with the desired suffix
### Python Check in String
In the string checking category it checks for the boolean of a string. When it meets the conditions then the value will be True, if the string does not meet the conditions then the value will be False
#### 1. isupper()
returns True if all letters in the string are uppercase, and returns False if only one of the letters is lowercase in the string.
#### 2. islower()
returns True if all letters in the string are lowercase, and returns False if only one letter is capitalized in the string.
#### 3. isalpha()
Returns True if all characters in the string are letters of the alphabet. If not then False
#### 4. isalnum()
Returns True value if all characters in the string are alphanumeric letters i.e. letters only or numbers only or both. If not then False
#### 5. ispace()
Returns true if the string contains only whitespace characters, such as spaces, tabs, newlines or other whitespace characters. If not then false
#### 6. istitle()
Returns true if the string contains a capital letter in every word and continues with lowercase letters. If not then False
### String Formatting
#### 1. zfill()
- Can add a numeric value of 0 to the left of a number or string
- The number of characters must be less than or equal to the zfill value
#### 2. Allighnment
- Align text right/left/center with rjust(), ljust(), and center()
- Add spaces to strings to make them match
- the parameter is an integer which is the overall test length (not the number added)
- The second parameter is used to replace the space
#### 3. String Leteral
A String Literal is a sequence of characters surrounded by quotation marks. We can use one, two, or three quotes for strings. Also, character literals are single characters surrounded by one or two quotes. Escape character is a backslash that allows inserting the characters ' and " in the string part

#### 4. Raw String
Python also provides a way to print strings according to any given input. Insert the letter r before the string opener

### List, Set, and String Operation
* len() : will returns the length of an object
* min() : return the lowest value
* max() : return the highest value
* count() : data occurens
### Operator, Operands and Expression
Operators are special symbols in Python that carry out arithmetic or logical computation. The value that the operator operates on is called the operand. Expression is a combination of operators and operands that is interpreted to produce some other value. Python divides the operators in the following groups:
- Arithmetic operators
- Assignment operators
- Comparison operators
- Logical operators
- Identity operators
- Membership operators
- Bitwise operators

### Conditional Expression
#### if condition
- In python the expression is placed after the if and the decision is based on the truth value of the expression
- If the expression evaluates to True, the statement block will be executed
- If the expression evaluates to false, then the next block (after the if) will be executed
#### else condition
- Can be combined with if statement, as a way out when the IF condition is false
- Else is optional and singular
#### elif condition
- Elif is short for else if
- Elif is an alternative to nested if
- An IF statement can be executed for one or more elif statements (optional and not restricted)



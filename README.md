# JavaScript-tutorial
This repo is to document my leaning journey of JavaScript 

# Data Types
- Undefined : ANything that hasnt been defined.
- null : Nothing.
- boolean : True or False.
- string : Text.
- symbol : A unique value.
- number : An integer or a number.
- object : It can store key value pairs.

# Variables 
- Data is set to or as variables.
- A lable to point to anyting it has been assigned to.

# Variable Declearation 
- These are variables the are decleared but have not been assigned a value
- var, let and const are the ways to declear variables in Javascript
- var : It works in the global scope of the program, it can work anywhere 
- let : It works in the local scope of the program, it only works in the scope it was decleared 
- const : It's value when assigned can never be changed
   eg: 
   var a; 
   let b; 
   const c;

# Vsrible Assignment 
- This is when the variable decleared is giving a value
   eg: 
   var a = 1; 
   let b = 2; 
   const c = 3;

# Loging 
- console.log() : this is a function for checking the values of variables or loging data in the console.

# Case Senitivity in Variables
- Varible and function names in Javascript are case sensitve
   eg:
   var UserName; is not equal to var USERNAME
   ie, the are two different variables

- NB : Camel case is mostly used in Javascript variable declearations
   eg:
   var userName;
   var studentDetails;

# Adding Numbers
- Adding numbers in Javascript is done using the '+' opperator
   eg:
   var sum = 10 + 10;

# Subtracting Numbers
- Subtraction in Javascript is done using the '-' opperator
   eg:
   var sub = 30 - 10;

# Multiplying Numbers
- Multiplication in Javascript is done using the '*' opperator
   eg:
   var sum = 10 * 2;

# Dividing Nubers 
- Division in Javascript is done using the '/' opperator
   eg:
   var div = 40 / 2;

# Incrementing Numbers 
- Increaseing numbers in Javascript is done by adding 1 or uing the '++'
   eg:
   var inc = 19;
   inc = inc++ or inc = inc + 1

# Decrementing Numbers 
- Decreaseing numbers in Javascript is done by subtracting 1 or uing the '--'
   eg:
   var dec = 21;
   dec = dec-- or dec = dec - 1

# Decimal Numbers
- They are refered to as Floating Point Numbers or Floats
   eg:
   var ourDecimal = 5.7;
   var myDecimal = 0.009;

# Multiplying Decimal Numbers
- Multiplying Decimals is equal to multiplying whole numbers 
   eg:
   var product = 2.0 * 2.5;

# Dividing Decimal Numbers
- Dividing Decimals is equal to dividing whole numbers
   eg:
   var quotient = 4.4 / 2.0;

# Finding a Reminder 
- THe remainder operator is represented by '%', and gives the remainder of the division of two numbers 
   eg:
   var remainder;
   remainder = 11 % 3;

# Compund Assignment with Augmented Addition and Subtraction
   eg: 
   var a = 8;
   a = a + 12  a = a - 5
   => a += 12  a -= 5

# Compund Assignment with Augmented Multiplication and Division
   eg: 
   var a = 8;
   a = a * 12  a = a / 5
   => a *= 12  a /= 5

# Declear String Variables
   eg: 
   var firstName = "Alan";
   var lastName = "Turing";

# Escaping Literal Quate in Strings
- Escape characters are used to escape default JS built in sysmnbols
   eg:
   var str = "Hello, is \"Hi\", is what he siad"

# Quating Strings Using Single Quates
- To avoid using escape characters, Javascript can use single quates or backticks instead os double, the the double quates can be used in the straing variable without escaping the characters
   eg:
   - var strSingleQuates = 'Hello, "Hi", is what he siad'
   - var strSingleQuatesBackTicks = `Hello, "Hi", is what he siad`

# Escaping Sequence in Strings
- Code Output 
   eg:
   \' - Single quote
   \" - double quote 
   \\ - backslash
   \n - newline
   \t - tab
   \b - backspace
   \f - form 
   
# Concatenating Strings with the Addition Operator
- String concatenation is the joining of two stings avd variable 
   eg:
   var ourStr = "I come first. " + "I come second."

# Concatenating String with Plus Equals Operator 
   eg:
   var ourStr = "I come first. "
   ourStr += "I come second. "

# Constructing Strings with Variables
- Varibles can be used in strings to make things easy if a data is going to be used in the code multiple times or data would be updated by the uses, it is decleared as a variable.
   eg:
   var ourName = "freeCodeCamp";
   var ourString = "Hllo, our name is " + ourName + ", hoe are you?"

# Appending Variables to String
- Appending is when a variable is already created but it is updated t=with another variable.
   eg:
   var anAdjective = "awesome!"
   var ourString = "freeCoedCamp is "
   ourStr += anAdjective

# Finding Lenght of Sring
- This is the use of a built in Javascript function to know the number of characters in a string. 
   eg:
   var nameLen = 0
   var name = "Stephen"
   nameLen = name.lenght

# Bracket Notation
- Javascript count from 0
   eg: 
   var firstLetter = ""
   var name = "Stephen"
   firstLetter = name[0]
   this will return "S"

# String Immutability
- Strings can not be altered once created but can be changed
   eg:
   var myStr = "Jello"
   myStr[0] = "H"
   this will not work do this instead
   myStr = "Hello"

# Bracket Notation to FInd Nth Character in  String
- Using the bracket notation one can find the position of the characters.
   eg:
   third position
   myStr[2]

# Bracket Notation to FInd the Last Character in  String
- This is achived with the help of the ".length" object
   eg:
   myStr[myStr.lenght -1]

# Sort Multiple Data with Array
- Arrays allows to store several peices of data in one place.
   eg: var ourArray = ["John", 23]

# Nested Array
- When an array has an array to be one of its elements, it is called a nested array or a multidimentional array
   eg:
   var ourArray = [["John", 23] ,["Guru", 24]]

# Access Array Data with Index
- Array data can be accessed using the index of the array elements 
   eg: 
   myArray[0]
   this returns - "John", 23

# Modify Array Data with Index
- Array index can be used to modify arrays 
   eg:
   myArray[0] = ["Stephen", 23]

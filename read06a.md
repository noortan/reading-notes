# In this section we will discuss two main topics :

* ####  Expressions and operators
* #### Functions

![operators in js!](https://image.slidesharecdn.com/loopscontinuedpdfv-150114103425-conversion-gate02/95/loops-in-javascript-2-638.jpg)



### Operators
JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

* Assignment operators
* Comparison operators
* Arithmetic operators
* Bitwise operators
* Logical operators
* String operators
* Conditional (ternary) operator
* Comma operator
* Unary operators
* Relational operators

JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:

operand1 operator operand2
### For example, 3+4 or x*y.

A unary operator requires a single operand, either before or after the operator:

operator operand
or

operand operator
### For example, x++ or ++x.

![Operators in js!](https://www.rdcircles.com/wp-content/uploads/2020/06/JavaScript-operators-RD-Circles.png)





### Expressions
An expression is any valid unit of code that resolves to a value.

Every syntactically valid expression resolves to some value but conceptually, there are two types of expressions: with side effects (for example: those that assign value to a variable) and those that in some sense evaluate and therefore resolve to a value.

The expression **x = 7 **is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to seven.

The code** 3 + 4 **is an example of the second expression type. This expression uses the + operator to add three and four together without assigning the result, seven, to a variable.

JavaScript has the following expression categories:

* Arithmetic: evaluates to a number, for example 3.14159. (Generally uses arithmetic operators.)
* String: evaluates to a character string, for example, "Fred" or "234". (Generally uses string operators.)
* Logical: evaluates to true or false. (Often involves logical operators.)
* Primary expressions: Basic keywords and general expressions in JavaScript.
* Left-hand-side expressions: Left values are the destination of an assignment.

## Functions
Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

![functions!](https://miro.medium.com/max/700/1*dAwQkc-E0j1AcpdPeGznzg.png)
### Defining functions
Function declarations
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

* The name of the function.
* A list of parameters to the function, enclosed in parentheses and separated by commas.
* The JavaScript statements that define the function, enclosed in curly brackets, {...}.

For example, the following code defines a simple function named square:

**function square(number) {
  return number * number;
}**
### Function expressions
While the function declaration above is syntactically a statement, functions can also be created by a function expression.

Such a function can be anonymous; it does not have to have a name. For example, the function square could have been defined as:

**const square = function(number) { return number * number }
var x = square(4) // x gets the value 16**
### Calling functions
Defining a function does not execute it. Defining it names the function and specifies what to do when the function is called.

Calling the function actually performs the specified actions with the indicated parameters. For example, if you define the function square, you could call it as follows:

*square(5);*
The preceding statement calls the function with an argument of 5. The function executes its statements and returns the value 25.

Functions must be in scope when they are called, but the function declaration can be hoisted (appear below the call in the code), as in this example:

**console.log(square(5));
/* ... */
function square(n) { return n * n }**
### Scope and the function stack
Recursion
A function can refer to and call itself. There are three ways for a function to refer to itself:

The function's name
arguments.callee
An in-scope variable that refers to the function
For example, consider the following function definition:

**var foo = function bar() {
   // statements go here
}**
Within the function body, the following are all equivalent:

1. bar()
2. arguments.callee()
3. foo()
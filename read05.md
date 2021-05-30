# In this section we will discuss two main topics :

* #### Expressions and operators
* #### Loops and iteration Focus on for and while loops

![operators in js!](https://image.slidesharecdn.com/loopscontinuedpdfv-150114103425-conversion-gate02/95/loops-in-javascript-2-638.jpg)

![loops in js!](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Loops-1200x675.jpg)

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

### Loops and iteration : 

Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

**for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
} **
There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.

The statements for loops provided in JavaScript are:

* for statement
* do...while statement
* while statement
* labeled statement
* break statement
* continue statement
* for...in statement
* for...of statement

### for statement
A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows:

**for ([initialExpression]; [conditionExpression]; [incrementExpression])**
  
  When a for loop executes, the following occurs:

1.  The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
 2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
3. The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
4. If present, the update expression incrementExpression is executed.
5. Control returns to Step 2.

![for in js!](https://i.ytimg.com/vi/L7nVZZQEnZU/maxresdefault.jpg)

### while statement
A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

**while (condition)
  statement** 
If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

To execute multiple statements, use a block statement ({ ... }) to group those statements.

 **let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}**  
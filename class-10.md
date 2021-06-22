## Error Handling & Debugging

JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.

## Code Debugging

Programming code might contain syntax errors, or logical errors.

Many of these errors are difficult to diagnose.

Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.

Searching for (and fixing) errors in programming code is called code debugging.

## JavaScript Debuggers

Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger.

Built-in debuggers can be turned on and off, forcing errors to be reported to the user.

With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.

Normally, otherwise follow the steps at the bottom of this page, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.

## ERROR OBJECTS CON TI NUED

1. Syntax Error SYNTAX IS NOT CORRECT This is caused by incorrect use of the rules of the language. It is often the result of a simple typo.

2. Ref erenceError VARIABLE DOES NOT EXIST . This is caused by a variable that is not declared or is out of scope

3. INCORRECT USE OF eval() FUNCTION The eval () function evaluates text through the interpreter and runs it as code (it is not discussed in this book). It is rare that you would see this type of error, as browsers often throw other errors when they are supposed to throw an Eva 1 Error

4. UR I Error NCORRECT USE OF URI FUNCTIONS If these characters are not escaped in URls, they will cause an error: / ? & I : ; CHARACTERS ARE NOT ESCAPED decodeURI('http : //bbc . com/ news . phpl l a=l') ; URlError : URI error

## HOW TO DEAL WITH ERRORS
1. DEBUG THE SCRIPT TO FIX ERRORS
2. HANDLE ERRORS GRACEFULLY
**HOW TO LOOK AT ERRORS IN FIREFOX**

![      error in firefox!](https://camo.githubusercontent.com/4e9d866c1885145e5f2b10a78e8a1cf3e6d4170525f49a72535f8d5ef5268453/68747470733a2f2f69322e77702e636f6d2f776f726470726573732e6f72672f737570706f72742f66696c65732f323032302f30372f66697265666f782d776562636f6e736f6c652e706e673f726573697a653d313032342532433630372673736c3d31)

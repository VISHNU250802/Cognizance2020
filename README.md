# Cognizance2020
<!-- Italics -->
## *Today's topic*:
# C++ FUNCTIONS
### A function is a block of code that performs a specific task.
### Dividing a complex problem into smaller chunks makes our program easy to understand and reuseable.
___
## TYPES OF FUNCTIONS:

<!-- Italics -->
- *1. Standard Library Functions: Predefined in C++*
- *2. User-defined Function: Created by users*
 #### we mainly focus on user-defined functions.
 ---
 # C++ USER-DEFINED FUNCTIONS
 - C++ allows the programmer to define their own function.
 - A user-defined function groups code to perform a specific task and that group of code is given a name (identifier).
 - when the function is invoked from any part of the program, it all executes the codes defined in the body of the function.
---
# C++ FUNCTION DECLARATION
### The syntax to declare a funcyion is:
#### returnType functionName (parameter1, parameter2,.....) {}
#### For example:
- // function declaration
void greet() {
    cout << "Hello World";
}
#### Here, 
- the name of the function is 
<!-- Strong -->
**greet()**
- the return type of the fuction is 
<!-- Strong -->
**void**
- the empty parentheses mean it doesn't have any parameters
the function body is written inside
<!-- Strong -->
**{}**
<!-- Italics -->
## *A simple example of declaration of a function in c++* 
![https://image.slidesharecdn.com/badshahprogramming-160814063418/95/functions-in-c-ppt-14-638.jpg?cb=1471156496]
___
# Calling a function
#### In the above program, we have declared a function named 
<!-- Strong -->
**greet()**
#### To use that function, we need to call it.By this way we can call a function
<!-- Strong -->
**greet()**
int main() {
     
    // calling a function   
    greet(); }
# FUNCTION PARAMETERS
#### As mentioned above, a function can be declared with parameters (arguments).A parameter is a value that is passsed when declaring a function.For example:
void printNum(int num) {
    cout << num;
}
#### Here, the 
<!-- Strong -->
**int** & **num**
#### variable,function parameter.
<!-- Italics -->
## *A small example of c++ function*

# JavaScript
## Expressions and Operators:

JavaScript has the following types of operators.
Assignment operators
Comparison operators
Arithmetic operators
Logical operators
String operators
Relational operators


## JavaScript Function:

A function is a series of statements that do something, such as calculate a value, perform a task, or complete another action. The difference between writing a function and just writing a bunch of statements is that a function encapsulates what you want to do. You get to use it again in a way similar to how we use variables to hold data types.


## Define a function using the keyword function, followed by a name, followed by parentheses. Insert the code to be executed by the function inside curly brackets and don't forget to add semicolons:

function sayHello() {
    alert("Hello");
};

You defined the function, but did not yet call or execute it.

Type sayHello(); to call the function by its name and a set of parentheses (). You just executed your function!

sayHello();

While this was a good step, we want a function that takes in some data (also called parameters) and does something with it.

## Make a version of sayHello() that greets you by name, like so:

function sayHello(name) {
  alert("Hello " + name);
};

Here we now have a function called "sayHello" that takes a parameter as an input in its parantheses called "name". Inside the function, we create an alert that displays "Hello " followed by the value of name that was input to the function.

Now call it with your name as a string in place of name. Don’t forget the quotes:

sayHello("Shadi hahahahha");

## return Keyword

// With return
function sum(num1, num2) {
  return num1 + num2;
}

Without return, so the function doesn't output the sum

function sum(num1, num2) {
  num1 + num2;
}

functions return (pass back) values using the return keyword. return ends function execution and returns the specified value to the location where it was called. A common mistake is to forget the return keyword, in which case the function will return undefined by default.



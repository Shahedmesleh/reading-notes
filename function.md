**function**:A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of statements).
***
Syntax:

function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
***simple ex:***

function say good moring()
decoument.write("good moring");

ex:
var x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
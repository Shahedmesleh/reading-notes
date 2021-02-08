**Comparison operators** — operators that compare values and return true or false. The operators include: >, <, >=, <=, ===, and !==.
ex:Equal to (===) — returns true if the value on the left is equal to the value on the right, otherwise it returns false.
***

**Logical operators** — operators that combine multiple boolean expressions or values and provide a single boolean output. The operators include: &&, ||, and !.
ex:&& (and) — This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
for example:
var isTrue = ('yellow' === 'green') && (4 >= 4); 

***

**The purpose of a while loop is to execute a statement or code block repeatedly as long as an expression is true.** 
Once the expression becomes false, the loop terminates.
Syntax
while (condition) {
  // code block to be executed
}
*ex:*
var i =0;

while(i < 5)
{
    console.log(i);
    i++;
}
***
**for loop:**
The JavaScript for/of statement loops through the values of an iterable objects.
 for/of lets you loop over data structures that are iterable such as Arrays, Strings, Maps, NodeLists, and more.
Syntax:
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
Statement 1 is executed (one)
ex:
let sum = 0;
for (let i = 0; i <= 9; i++, sum += i);
console.log(sum);
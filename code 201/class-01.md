
## Introductory HTML and JavaScript

## HTML Structure
HTML uses elements to describe the Structure of Pages
Each element has an opening tag and a closing tag.
Tags act like containers. They tell you something about the information that lies between their opening and closing tags.
Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.
Extra markups
Block level elements : elements that always appear to start on a new line in the browser window. These are known as .

Examples of block elements are

<h1>, <p>, <ul>, and <li>.

Inline elements : elements that always appear to continue on the same line as their neighbouring elements. .

Examples of inline elements are

<a>, <b>, <em>, and <img>.

Process & Design
important information to search and collect about the audience
Understand who your target audience is.
Audience influence design decisions from color palettes to level of detail in descriptions.
Consider Why people are visiting your website and what they are trying to achive.
what information they need in order to achieve their goals quickly and effectively.
How often people will visit your site will effect the updaing of your websites
Create a Site map.
A wireframe is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.
Connect your design to the aim of the websi
JavaScript Operators JavaScript has the following types of operators:

Assignment operators Comparison operators Arithmetic operators Bitwise operators Logical operators String operators Conditional (ternary) operator Comma operator Unary operators Relational operators An expression is any valid unit of code that resolves to a value. JavaScript has the following expression categories:

Arithmetic: evaluates to a number, for example 3.14159. (Generally uses arithmetic operators.) String: evaluates to a character string, for example, "Fred" or "234". (Generally uses string operators.) Logical: evaluates to true or false. (Often involves logical operators.) Primary expressions: Basic keywords and general expressions in JavaScript. Left-hand-side expressions: Left values are the destination of an assignment. For statement A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows:

for ([initialExpression]; [conditionExpression];[incrementExpression]) statement

while statement A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition) statement oops offer a quick and easy way to do something repeatedly.

There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times,The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.

The statements for loops provided in JavaScript are: for statement: A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows: for ([initialExpression]; [conditionExpression]; [incrementExpression]) statement When a for loop executes, the following occurs: The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.) The statement executes. To execute multiple statements, use a block statement ({ ... }) to If present, the update expression incrementExpression is executed. Control returns to Step 2. i.g: for (let step = 0; step < 5; step++) { // Runs 5 times, with values of step 0 through 4. console.log('Walking east one step'); } do…while statement

The do…while statement repeats until a specified condition evaluates to false. A do…while statement looks as follows:

do statement while (condition); statement is always executed once before the condition is checked. (To execute multiple statements, use a block statement ({ ... }) to group those statements.).

The do…while statement executes at least once even if the condition is false.

i.g: let i = 0; do { i += 1; console.log(i); } while (i < 5); while statement A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition) statement How it works: If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

i.g: The following while loop iterates as long as n is less than 3: let n = 0; let x = 0; while (n < 3) { n++; x += n; }



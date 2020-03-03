# Function Notes

<p>Script – a series of instructions that a computer can follow to achieve a goal, like a recipe, handbook manual.  

A browser may use different parts of the script depending on how the user interacts with the page.  Scripts can run different sections of the code in response to the situation around them.  

-  Define the goal: puzzle for computer to solve
-  Design the script: split the goal into a series of tasks such as a flowchart.  Work out each step to complete the task.  
-  Code each step: write in a programming language, like Javascript</p>

Expression pg. 74

<p>What is a Function?

Functions let you group a series of statements together to perform a specific task.  If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements.)

Functions consist of a series of statements that have been grouped together because they perform a specific task.  A method is the same as a function, except methods care created inside (and are a part of) an object.

* HTML
	- html
	- Head/Head
	- Body
	- h1
	- script src=”js/basics-function.js”></
	- /body
	- /html

* JS
	var msg = ‘Sign up to receive our newsletter for 10% off!’;
	function updateMessage() {
		var el = document.getElementById(‘message’);
		el.textContent = msg;
}
updateMessage(); </p>

<p>You declare a function using the function keyword.
Give the function a name (sometimes called identifier) followed by parenthesis.  The statements that perform the task sit in a code block (they are inside curly braces).

function sayHello() {
	document.write(‘Hello!’);

function=function keyword; sayHello=function name; code block in curly braces

If a function needs information work, you indicate what it needs to know in parenthesis after the function name.  The items inside these () are knows at the parameters of the function.  Inside the function those words act like variable names.</P>


* function getArea(width, height){		
* return width * height;	
- the parameters are used like variables w/in the function
- width,height paramenter
}

<p>Arguments as values:  When the function below is called, the number 3 will be used for width of the wall, and 5 will be used for its height.
	
getArea(3,5);

Arguments as variables: You do not have to specify actual values when calling a function – you can use variables in their place.  So the following does the same thing.

	wallWidth = 3;
	wallHeight = 5;
	getArea(wallWidth, wallHeight);


Some functions return information to the code that called them eg. when peform a calculation, return a result.

The calculateArea() function returns the area of a rectangle to the code that called it.  Inside the function, a variable called area is created.  It holds the calculated area of the box.  The return keyeword is used to return a value to the code that called the function.</P>

* function calculateArea(width, height) {
	- var area = width * height
	- return area
- }
- var wallOne = calculateArea(3, 5);
- var wallTwo = calculateArea(8, 5);

This also demonstrates how the same function can be sued to perform the same steps with different values.</P>

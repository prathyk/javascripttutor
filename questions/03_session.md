Program Structure
=================

Read
----
* [Chapter 2](http://eloquentjavascript.net/02_program_structure.html)

## Questions
1. What is the difference between an _expression_ and a _statement_? 
1. Is _let_ a valid binding name?
1. Which of the following are valid javascript values?
	* integers
	* strings
	* functions
1. Replace `???`, so that `my name is Rob` gets printed to console
	```javascript
	var myFunc = ???;
	myFunc("my name is Rob");
	```
1. What will happen if you give a string as input to the following program?
	```javascript
	let theNumber = Number(prompt("Pick a number"));
	console.log("Your number is the square root of " +
	            theNumber * theNumber);
	```
1. Write a program which presents two prompts to take two numbers `a` and `b` and prints a<sup>b</sup>
	1. Using `while` loop
	1. Using `for` loop
1. Explain the behavior of the following program
	```javascript
	console.log(""==true);
	console.log("false"==true);
	```
1. What is the difference between `continue` and `break` keywords?
1. What will be the output of the following program when we enter "rainy"? Explain.
	```javascript
	switch (prompt("What is the weather like?")) {
	  case "rainy":
		console.log("Remember to bring an umbrella.");
	  case "sunny":
		console.log("Dress lightly.");
	  case "cloudy":
		console.log("Go outside.");
	  default:
		console.log("Unknown weather type!");
	}	
	```

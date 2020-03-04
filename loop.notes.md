# Loop Notes

You can evaluate a situation by comparing one value in the script to what you expect it might be.  The result will be Boolean: true or false.

<p> == is equal to

    This operator compares two values (numbers, strings or Booleans) to see if they are the same.
	‘Hello’ == ‘Goodbye” returns false
	‘Hello’== “Hello’ returns true because the are the same string.
=== strict equal to

	This operator compares two values to check that both data type and value are the same.

!= is not equal to

This operator compares two values (numbers, strings or Booleans) to see if they are not the same.

	‘Hello’ != ‘Goodbye’ returns true

    !== strict not equal to
	‘3’ ! == 3

Testing or checking the condition as evaluating.  Every value can be treated as true or false even if it is not a Boolean true of false value.  In a short-circuit evaluation, a condition might not need to run.

<h3>Logical Operators</h3>

Comparison operators usually return single values of true or false.  Logical operators allow you to compare the results of more than one comparison operator.  

	&& tests more than one conditions
	|| tests at least one condition
	! logical not takes a single Boolean value and inverts it

Logical expressions are evaluated left to right.  If the first condition can provide enough info to get the answer, there is no need to evaluate the second condition.

Loops, Loop Counters, Looping

Loops check a condition.  If it returns true, a code block will run.  Then the condition will be checked again and if it still returns true, the code will run again.  It repeats until the condition returns false.

3 Common Types of Loops:
- For:  If you need to run a code a specific number of time (most common).  The condition is usually a counter which is used to tell how many times the loop should run.
- While: If you don’t know how many times the code should run.  Condition can be something other than a counter, code will continue to loop for as long as the condition is true,
- Do While:  Very similar to while loop, but key difference: it will always run statements inside the curly braces at least once, if the condition evaluates to false.

    - for (var I = 0; I < 10; i++) {
	    - document.write(i);
}

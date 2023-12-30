# Operators and Loops

## 1. What is an ```expression``` in JavaScript?

* An expression in JavaScript is a combination of values, variables, operators, and function calls that evaluates to a single value. It's a fundamental building block of JavaScript code.

* It can be as simple as a single number or variable, or it can involve more complex calculations and operations.

## 2. Why would we use a loop in our code?

* Loops are used to repeat a block of code multiple times. This is essential for various tasks in programming, including:

  * Automating repetitive tasks: Loops can perform the same actions on multiple items of data, saving time and effort.

  * Iterating over collections of data: Loops are used to access and process each item in an array, string, or other data collection.

  * Making code more concise: Loops can condense code that would otherwise require multiple repetitive statements.

## 3. When does a ```for``` loop stop executing?

* A ```for``` loop stops executing when one of two conditions is met:

  1. The counter variable reaches the end of the specified range: The ```for``` loop has a built-in counter variable that is initialized, tested for a condition, and updated after each iteration. Once the counter reaches the end of the specified range, the loop terminates.

  2. A break statement is encountered within the loop body: A ```break``` statement can be used to prematurely exit a ```for``` loop, even if the counter hasn't reached the end of the range.

## 4. How many times will a ```while``` loop execute?

* The number of times a while loop executes depends on the condition within the loop:

  * It will continue to execute as long as the condition remains true.

  * If the condition never becomes false, the loop will run indefinitely (potentially causing a problem known as an infinite loop).

  * It's essential to ensure that the condition within a ```while``` loop will eventually become false to avoid infinite loops.
  
 
# TDD Workshop - JavaScript

## Setup
* Node.js
* npm
* Visual Studio Code
* Mocha
* Sinon

Note: If modules installed globally, use npm link module-name in project directory

## New Code Exercise: Test Drive Creating a Calculator
* Create a Calculator class with an Add method.
* The method can take 0, 1 or 2 numbers, and will return their sum. 
* For example: “” or “1” or “1,2”.
* For an empty string it will return Zero.
* Allow the Add method to handle an unknown amount of numbers.
 
 ## Legacy Code Exercise: Test Drive Refactoring an Existing Class
* Create a String Calculator class with an Add method that takes in Strings.
* Inject the String Calculator into the Calculator using a constructor.
* Have the Calculator class delegate to the String Calculator class.

## Optional
* Create a Numeric Calculator class with an Add method.
* Inject the Numeric Calculator into the Calculator using a setter method.
* If the Add method is called with string parameters, delegate to the String Calculator; if the Add method is called with numeric parameters, delegate to the Numeric Calculator.

Exercises based on [TDD Kata by Roy Osherove](http://osherove.com/tdd-kata-1/)
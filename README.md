# String Calculator Kata Lite
The following is a TDD Kata, an exercise in coding, refactoring and test-first.  
This is a smaller version of the [String Calculator Kata](https://github.com/jarlehansen/string-calculator-kata).

## Before you start
* Try not to read ahead.
* Do one task at a time. The trick is to learn to work incrementally.
* Make sure you only test for correct inputs. There is no need to test for invalid inputs for this kata.

## The kata

### Step 1: the simplest thing
Create a simple String calculator with a method `int add(String numbers)`.

* The string argument can contain 0, 1 or 2 numbers, and will return their sum (for an empty string it will return 0) for example `""` or `"1"` or `"1,2"`.
* Start with the simplest test case of an empty string and move to one and two numbers.
* Remember to solve things as simply as possible so that you force yourself to write tests you did not think about.
* Remember to refactor after each passing test.

### Step 2: handle an unknown amount of numbers
Allow the `add()` method to handle an unknown amount of numbers.

Text adapted from [xpeppers](https://github.com/xpeppers/string-calculator-kata).  
Credits to [Roy Osherove](http://osherove.com/tdd-kata-1) for the original idea.
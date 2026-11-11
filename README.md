
# CMSC 115 – Unit 8 Lab 2: AI + JUnit + Git

GitHub Repository:
https://github.com/ndohketurah-svg/cmsc115_unit8_lab2

## Iteration 1: Initial AI-Generated Code

I used AI to help create the first version of the findResult() method. The code added all the numbers in the array and returned their sum.

For the sample array {3, 7, 2, 9, 4}, the result was 25.

I learned that code can run and produce an output without necessarily meeting all the assignment requirements. I also encountered a compilation error caused by an extra closing brace, which I corrected.

JUnit results: The first attempt received 0/45 because of the compilation error. I did not record a separate complete JUnit result after correcting the braces.

## Iteration 2: Finding the Largest Number

I changed the method so that it searched through the array and returned the largest number instead of adding all the numbers.

For the sample array {3, 7, 2, 9, 4}, the result changed from 25 to 9.

This was an improvement because the method now looked for the maximum value. However, it still had a problem: accessing values[0] would cause an error if the array was empty.

JUnit results: I did not record a separate JUnit score for this iteration.

## Iteration 3: Handling Empty Arrays

I improved the code by adding a condition that checks whether the array is empty. If it is empty, the method returns Integer.MIN_VALUE. Otherwise, it finds and returns the largest number.

For the sample array {3, 7, 2, 9, 4}, the result was 9.

This version handles the empty-array case without trying to access a nonexistent element.

JUnit results: I received 25/40 on a submission during this stage. The final code still needs to be checked against the complete test results.

## Final Reflection

This lab helped me understand how AI, JUnit testing, and Git can work together during software development. I learned that AI-generated code should always be reviewed and tested because it may compile successfully but still produce the wrong result.

I also learned how important it is to check edge cases, such as an empty array, and how GitHub commits can document changes made throughout a project.

The biggest lesson I learned is that testing and debugging are important parts of programming, not just writing code.

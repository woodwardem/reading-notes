# Lecture Notes Assignment
For Loops Review and Intro to Callback Functions

# ✍️ Notes

1. What are loops used for in programming?
    * Loops offer an easy way to do something repeatedly. They can run the same code over and over again just getting different results. 
2. What are the 5 different types of loops we work with in JavaScript?
    * for loop: loops through a block of code a number of times.
    - while loop: loops through a block of code while a specified condition is true.
    - do..while: also loops through a block of code while a specified condition is true. 
    - for..in: loops through the properties of an object.
    -for...of: loops through the values of an iterate object.
3. What is the definition of a for loop?
    * The for statements creates a loop that consists of three optional expressions, enclosed is parenthesees and seperated by semicolons, followed by a statement(usually a block statement) to be executed in the loop. 
4. What is the syntax and pseudocode of a for loop?
    * for (initialExpression(i=0;); conditionalExpression; iteratorExpression) {
        code block to run at every iteration;
    }
5. What does the initial expression do?
    * is ran once at the very begining of the for loop and it initializes the variable used in the loop. let i=0;
6. Why is it important to use `let` when declaring the `i` variable in a loop?
    * When let is used to declare the i variable in a loop, the i variable will only have scope within the loop. 
7. What does the conditional expression do?
    * defines the condition for the loop to run. If condition returns true, the loop will start over again, if it returns false, the loop will end. 
8. What does the iterator expression do?
    * increments/decrements the value of the initial variable and moves the loop to the next iteration. 
    i++;
    i--;
9. When a for loop executes, the following occurs:
    * 1. the initializing expression is executed once and initializes a loop counter. 
    2. the conditional expression is evaluated. If it evaluates to true, the loop statements execute. If it evaluates to false, the for loop ends. 
    3. the statements inside the code block execute. 
    4. Then, the iterator expression is executed and either increments or decrements the loop to the next iteration. 
    5. Lastly, we circle back up to step 2 and the for loop continues to run until the condition returns false. 
10. What is a callback function?
    * 
11. When do we use a callback function?
    * your answer goes here...


# Resources
- [MDN on Loops and Iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)
- [MDN on the for statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)
- [w3Schools on For Loop](https://www.w3schools.com/js/js_loop_for.asp)
- [w3Schools on Callback Functions](https://www.w3schools.com/js/js_callback.asp)
- [MDN on Callback Functions](https://developer.mozilla.org/en-US/docs/Glossary/Callback_function)
# Lesson 3.04: Debugging and Scope

## Learning Objectives
Students will be able to... 
* Define and identify: **scope, aliasing, stack trace**
* Understand that changing a list in a function updates the list outside of the function
* Understand that updating variables in a function does not affect the variable outside of the function
* Understand global variables
* Draw a simple stack trace

## Materials/Preparation
* [Do Now]
* [Lab - Aliasing & Scope]
* Associated Reading - section 3.4 of Book
* Read through the do now, lesson, and lab so that you are familiar with the requirements and can assist students.

## Pacing Guide
| **Duration**   | **Description** |
| ---------- | ----------- |
| 5 Minutes  | Do Now      |
| 10 Minutes | Lesson      |
| 30 Minutes | Lab/Review         |
| 10 Minutes | Debrief  |

## Instructor's Notes
1. **Do Now**
    * Students have a chance to think about what & discuss what concepts they have been most challenged by.
    * Next, students practice passing a list as an argument and updating that list within the function. 
2. **Lesson**
    * Discuss what students observed in the Do Now and take time, if needed, to go over questions about concepts that students find challenging. 
    * Explain the concept of **aliasing**. You can draw on the board a diagram of the variable pointing to a list. Note that when passing the location of a list you are not passing the actual value, so the list can be changed. 
    * **Scope** of functions
        * Explain to students that variable scope is the part of a program where a variable is accessible
        * A variable which is defined in the main body of a file is called a global variable. 
        * Global variables: variables defined outside of a function and used in many different functions. 
        * To use global variables defined outside the function you must declare the varaible with the phrase `global name_of_variable`.
        * Any variable created inside of a function is a local variable.
        * Variables in functions include the function parameters, the variables defined in the function and variables declared as global. 
        * Local variables of functions can't be accessed from outside when the function call has finished.
        * Explain global variables are often used for constants.
        * NOTE: We use the 'ALL CAPS' convention for global variables.
            * Discuss that programming languages frequently have conventions like camelCase for function names, ALL_CAPS for globals, and underscore_separated for variables. It helps make code more readable, but isn't essential to functionality (in most cases)
   	    * Demonstrate how to draw the Stack Diagrams shown in the course book (found in section 3.4) and explain how they show the scope of variables as they related to functions.
   	    * Point out the error messages that will occur if you use a variable out of it's scope.
    * Debugging
        * Help students follow their program to understand how the code is working
        * Explain how the use of print statements throughout your code can let you know where in the program things are not operating as expected.
3. **Lab**
    * This lab has students running code that gets them thinking about aliasing and scope. They must also create a stack trace for a program to show their understanding of scope.

4. **Debrief**
    * Take time to review the concepts covered today: **scope**, **aliasing**, and **stack traces**. 
    * Call a few students to the board to draw their stack traces from the lab and talk through them.

### Accommodation/Differentiation    
If students are moving quickly, they can look ahead at the project spec or research the game Oregon Trail for context.

## Forum discussion
[Lesson 3.04: Debugging and Scope (TEALS Discourse Account Required)](https://forums.tealsk12.org/c/2nd-semester-unit-3-functions/lesson-3-04-debugging-and-scope)

[Do Now]:do_now.md
[Lab - Aliasing & Scope]:lab.md

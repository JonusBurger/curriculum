### Introduction

One of the challenges of programming is dealing with large amounts of data. For example, if you want to store the names of all the students in your class, how would you do it? You could create a variable for each name, but that would be tedious and inefficient. It'll also be hard to manage and update. What if you want to change or access the names later?

Luckily, there is a better way to handle this problem. In this lesson, you’ll learn about arrays, which are data structures that can store multiple values in a single variable. Arrays are very useful for organizing and manipulating large amounts of data. You’ll also learn about loops, which are control structures that allow you to execute a block of code repeatedly. Loops are very handy for performing the same operation on each element of an array. Finally, you’ll be introduced to Test-Driven Development (TDD), which is the practice of writing tests for your code before you write the code itself.

### Lesson overview

This section contains a general overview of topics that you will learn in this lesson.

- Using arrays.
- Using built-in array methods.
- Using loops.
- Getting your hands dirty with TDD exercises.

### Arrays

Strings and numbers may be our building blocks, but as your scripts get more complex, you're going to need a way to deal with large quantities of them. Luckily, JavaScript has a couple of data types that are used for just that. An Array is an ordered collection of items (Strings, numbers, or other things).

1. Go through [JavaScript Arrays from W3Schools](https://www.w3schools.com/js/js_arrays.asp).
1. [JavaScript Array Methods](https://www.w3schools.com/js/js_array_methods.asp) covers some of the most useful built-in array methods. These fundamentals are something you'll use every day, so don't rush too much and miss out!
1. This [JavaScript Arrays crash course](https://www.youtube.com/watch?v=7W4pQQ20nJg) explains an overview of arrays in JavaScript in about 6 minutes.

### Loops

Computers don't get tired, and they're really, *really* fast! For that reason, they are well suited to solving problems that involve doing calculations multiple times. In some cases, a computer will be able to repeat a task *thousands* or even *millions* of times in just a few short seconds where it might take a human many hours. \(Obviously, speed here depends on the complexity of the calculation and the speed of the computer itself\). One way to make a computer do a repetitive task is using a **loop**.

1. Read [MDN's Looping Code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code). It's a longer one, but make sure you tackle the 'Active Learning' sections at the bottom of the page.
1. Once again, same info, slightly different context from [JavaScript.info's "Loops: While and For"](http://javascript.info/while-for). Be sure to do the exercises at the end of the page. You learn best by doing.

### Test Driven Development

Test Driven Development \(TDD\) is a phrase you often hear in the dev world. It refers to the practice of writing automated tests that describe how your code should work before you actually write the code. For example, if you want to write a function that adds a couple of numbers, you would first write a test that uses the function and supplies the expected output. The test will fail before you write your code, and you should be able to know that your code works correctly when the test passes.

In many ways, TDD is much more productive than writing code without tests. If we didn't have the test for the adding function above, we would have to run the code ourselves over and over, plugging in different numbers until we were sure that it was working... not a big deal for a basic `add(2, 2)`, but imagine having to do that for more complicated functions, like checking whether or not someone has won a game of tic tac toe: \(`game_win(["o", null,"x",null,"x",null,"x", "o", "o"])`). If you didn't do TDD, then you might actually have to play multiple games against yourself just to test if the function was working correctly!

We will teach you the art of actually writing these tests later in the course. For now, you will continue to work on the JavaScript exercises from before.

### Assignment

<div class="lesson-content__panel" markdown="1">

1. Go back to the [JavaScript exercises repository](https://github.com/TheOdinProject/javascript-exercises) that we introduced in the [Data Types and Conditionals](https://www.theodinproject.com/lessons/foundations-data-types-and-conditionals) assignment. Review each README file prior to completing the following exercises in order:
    - `06_repeatString`
    - `07_reverseString`
    - `08_removeFromArray`
    - `09_sumAll`
    - `10_leapYears`
    - `11_tempConversion`

    Note: Solutions for these exercises can be found in the `solution` folder of each exercise.

</div>

### Knowledge check

The following questions are an opportunity to reflect on key topics in this lesson. If you can't answer a question, click on it to review the material, but keep in mind you are not expected to memorize or master this knowledge.

- [What is an array?](https://www.w3schools.com/js/js_arrays.asp)
- [What are arrays useful for?](https://www.w3schools.com/js/js_arrays.asp)
- [How do you access an array element?](https://www.w3schools.com/js/js_arrays.asp)
- [How do you change an array element?](https://www.w3schools.com/js/js_arrays.asp)
- [What are some useful array properties?](https://www.w3schools.com/js/js_arrays.asp)
- [What are some useful array methods?](https://www.w3schools.com/js/js_array_methods.asp)
- [What are loops useful for?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code#why_bother)
- [What is the break statement?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code#exiting_loops_with_break)
- [What is the continue statement?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code#skipping_iterations_with_continue)
- [What is the advantage of writing automated tests?](#test-driven-development)

### Additional resources

This section contains helpful links to related content. It isn't required, so consider it supplemental.

- It looks like this lesson doesn't have any additional resources yet. Help us expand this section by contributing to our curriculum.

# swe-sr-1-1

Welcome to your first short response assignment! If the code that you write is what gets your foot in the door for a job interview, how you communicate is what will get you the job. So, treat these assignments seriously! Write your responses as if you were planning on publishing them in a blog for the world to see (and, if you're confident, actually publish them!).

## Setup

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

Here are some useful commands to remember.

```sh
npm i                   # install dependencies
git checkout -b draft   # switch to the draft branch before starting

git add -A              # add a changed file to the staging area
git commit -m 'message' # create a commit with the changes
git push                # push the new commit to the remote repo
```

## Prompt

Imagine you are teaching a brand new programmer a brief lesson about functions and function calls. Your lesson should have the following components:

* A technical definition ("According to MDN, a function is...").
* An explanation of the concept with an analogy ("You can think of a function a ...")
* An example of the syntax for an arrow function using a JavaScript code block (triple backticks)
* An explanation of the syntax using the terms **arrow function**, **parameter**, **code block**, **return statement**, and **call/invoke**.

Below, we've provided an outline for your response but feel free to modify it as you see fit.

### Response

[Replace with your explanation of the concept with an analogy]

According to MDN a function is =
"A JavaScript function is a block of code designed to perform a particular task. A JavaScript function is executed when something invokes (calls) it."

Okay so this is how I made sense of functions:
A function is like a calculator.
You press buttons and give it some numbers (those are the parameters), and the calculator knows what to do — like add, subtract, whatever (that’s the code block).
When you hit the “=” button, that’s like calling the function — you’re telling it to run.
And the number that shows up on the screen? That’s the return value — the answer it gives you back.
So yeah, a function is basically just a little machine that takes some input, does something, and gives you an output. Once I thought of it like that, it started to click.


Check out this example:

```js
// const addNumbers = (a, b) => {
return a + b;
};
// calling (invoking) the function
let result = addNumbers(5, 3); 
// result will be 8) console.log(result);
```


To break it down line by line =
const addNumbers = (a, b) => { ... }
This is an arrow function assigned to a constant named addNumbers.
(a, b) are the parameters — these act like placeholders for the values you pass into the function.
The { return a + b; } part is the code block — it’s the section where the function does its work.
The line return a + b; is the return statement — it tells the function what value to give back to the place where it was called.
addNumbers(5, 3); is how we call (or invoke) the function — we’re telling it to run with 5 and 3 as the inputs.



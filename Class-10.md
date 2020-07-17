# Chapter 10, Error handling and debugging
- Every statement in a script lives in one of three execution contexts

  - **Global context**, code that is in the script but not in a function.

  - **Function context**, code that is being run within a function.

  - **Eval context**, text is executed like code in an internal function.

- Debugging is the process of finding errors. The console can help narrow down the area in which the error is located.

  - The console proves to be more and more helpful each day, logging things when we aren't sure what a value is returning.
 
- Javascript has several different types of errors. Each creates its own error object which can tell you the line number and a description of the error!

### The Stack
- The javacsript interpreter processes one line of code at a time. When a statement needs data from another function, it stacks the new function on top of the current task.


















- Back to main page [Click here](README.md)
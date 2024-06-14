# Frontend Interview Question and Answers
This repo contains the list of questions and answers commonly asked in interviews

## HTML
- work in progress

## CSS
- work in progress

## OOPs
- work in progress

## JavaScript

1. **Block Scope vs Local Scope**
   * In local scope, variables are typically defined within a function
   * While block scope is created within code blocks like if, for, or while statements.

2. **What is Callback hell?**
   * Callback hell, also known as the "pyramid of doom"
   * It is a phenomenon in JavaScript that occurs when multiple callback functions are nested inside each other.

3. **How many arguments hold promise in JavaScript?**
   * Two Arguments
   * Resolve and Reject

4. **What is map filter and reduce in javascript?**
   * Map, reduce, and filter are all array methods in JavaScript.
   * `map():` the map method is used to create a new array from an existing one.
   * `filter():` removes elements that are not required and creates a new array containing the ones needed.
   * `reduce():` reduces all array elements into a single value.

5. **How many scopes are in Javascript?**
   * Mainly Four scopes
      * Global Scope
      * Local Scope
      * Block level scope
      * **Lexical scope:** is the ability of a function scope to access variables from the parent scope.

6. **What is closure in JavaScript?**
   * A **closure** is the combination of a function bundled together or nested function.
   * A closure gives you access to an outer function's scope from an inner function.

7. **What is Hoisting?**
   * Hoisting is JavaScript's default behavior of moving declarations to the top.
   * A variable can be *used* before it has been declared.
   * let, var, const, normal function will be hoisted
   * but `let, const` will go to *Temporal Dead Zone* so *we'll get error*
   * JavaScript only hoists declarations, not initializations.
   * function expression and class expression will **NOT** be hoisted
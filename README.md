# Frontend Interview Question and Answers
This repo contains the list of questions and answers commonly asked in interviews

## Categories

- ### [HyperText Markup Language(HTML)](https://github.com/sailendrachettri/frontend-interview-questions-answer-for-freshers?tab=readme-ov-file#html)
- ### [Cascading Style Sheets(CSS)](https://github.com/sailendrachettri/frontend-interview-questions-answer-for-freshers?tab=readme-ov-file#css)
- ### [Object Oriented Programming(OOP)](https://github.com/sailendrachettri/frontend-interview-questions-answer-for-freshers?tab=readme-ov-file#oops)
- ### [JavaScript(Js)](https://github.com/sailendrachettri/frontend-interview-questions-answer-for-freshers?tab=readme-ov-file#javascript)


## HTML
1. **What is HTML?**
   * HTML stands for HyperText Markup Language. 
   * It is used to design web pages using a markup language. 
   * HTML is a combination of Hypertext and Markup language. 
   * Hypertext defines the link between the web pages. 
   * The markup language is used to define the text document within the tag which defines the structure of web pages.

2. **What are the various markup languages available?**
   * HTML: Hypertext Markup Language
   * KML: Key whole Markup Language
   * MathML: Mathematical Markup Language
   * SGML: Standard Generalized Markup Language
   * XHTML: eXtensible Hypertext Markup Language
   * XML: eXtensible Markup Language

3. **What is !DOCTYPE?**
   * The doctype is not an element or tag, it lets the browser know about the version of or standard of HTML

4. **Difference between HTML Tag & HTML Element**

   **HTML Tag**
   * Either opening or closing is used to mark the start or end of an element.
   * Used to hold the HTML element.
   * Starts with < and ends with >

   **HTML Element**
   * Collection of a start tag, end tag, and its attributes.
   * Holds the content.
   * Whatever is written within an HTML tag are HTML elements.

5. **What are the various heading tags and their importance?**
   * There are 6 levels of headings defined by HTML. 
   * These six heading elements are H1, H2, H3, H4, H5, and H6
   * With H1 being at the highest level and H6 at the least.

6. **How to redirect to a particular section of a page using HTML?**
   * One can use the anchor tag to redirect to a particular section on the same page.

7. **What are attributes?**
   * An attribute is used to provide extra or additional information about an element.

8. **What is the use of alt attribute in images?**
   * The img alt attribute is used to specify the alternate text for an image.

9. **What are the different types of lists in HTML?**
   * Unordered List: It will list the items using plain bullets.
   * Ordered List: It will use different schemes of numbers to list your items.
   * Definition List: It arranges your items in the same way as they are arranged in a dictionary.

10. **What is the difference between block and inline elements?**
   * Block level elements would create a new line of content, stacking on top
of one anther.
   * Inline elements stay within the flow of what surrounds them.


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
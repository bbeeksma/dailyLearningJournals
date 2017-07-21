# Code 301, day 10

### Scope
  - Global scope, local scope.  Pref using local scope for variables.  
  - Can use IIFEs to set up modules to set up local scopes inside of your file.  Export only the things you want to use elsewhere.  Keeps things that you don't need elsewhere wrapped up.  Keep it secret keep it safe.

### Functional Programming
  - Variables are scoped to functions in javascript - see above.
  - Some functional features are built into javascritpt as the array methods
  - immutability = not changeable, don't mutate the data because it can cause bugs and other problems, once you mutate the data you can't get back the original.  Sometimes you can unintentionally modify some data but need it later.  Look for ways in code to not change a variable's value (slice instead of splice for example).
  - Imperative = describe what you want to happen instead of how to go through each step to get it done.
  - pure functions take an input, and give an output, don't update or store data anywhere.  impure functions modify data somehow.
  - higher-order functions = function that takes a function as argument, or returns a function as result.
  - Idea is to make programs more understandable, maintainable, reliable, and performant.

### Arrow functions
  - shorter syntax
  - this not bound in an arrow function, instead it keeps any meaning it already had.

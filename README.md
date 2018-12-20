# Javascript ES6
Notes on what I've learned in ES6.

## Array Helper Methods
* forEach
   * Accepts a function as a parameter and executes code against each element in the array. This replaces the standard "for"         loop when iterating over an entire array.
*map
   *Accepts a function as a parameter and executes code against each element in the array. Returns a new array of the same size     as the initial array.
* filter
   * Accepts a function as a parameter and executes code against each element in the array. Each element is evaluated against conditional logic implemented in the passed function. Returns a new array of items that passed the conditional test.
* find
   * Accepts a function as a parameter and executes code against each element in the array searching for a match. Finds the        first item that satisfies the conditional logic and returns it.
* every
   * Accepts a function as a parameter and each element is evaluated against conditional logic implemented in the passed function. Returns true or false depending on whether or not all elements in the array meet the conditional logic.
* some
   * Accepts a function as a parameter and each element is evaluated against conditional logic implemented in the passed function. Returns true  or false depending on whether or not some elements in the array meet the conditional logic.
* reduce
   * Accepts two parameters: a reducer function and an initial value. The reducer function itself accepts two parameters: an accumulator and a current value.  The reduce helper will output a single value. 


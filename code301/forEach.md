# ✍️ Notes

1. What is the definition of forEach?
    *  Array.forEach allows you to iterate through an array and executes a provided function once for each array element. 
2. What data type can you call forEach on?
    *  It is implemented as a method on an array. 
3. What does the pseudocode for forEach look like?
    *  array.forEach(callback(currentValue, index, arr), thisValue);
4. What are the 2 input arguments for forEach?
- callback and thisValue
   
5. What are the arguments the callback function takes in?
    *  *  1. current value: required, the value of the current element in the array that forEach is looking at. 
    2. index: Optional. The array index of the currentValue. 
    3. OPTIONAL: array:, 
6. What is currentValue referring to?
    *  The value of the current element in the array that forEach is looking at. 
7. What is the output of forEach?
    *  Undefined is the output of forEach. 
8. Does forEach mutate the original array?
   *  By default, foreach does not mutate the original array. 
9. What does it mean when an argument is optional?
   * It means that the funcion doesn't require that argument but you can put it in if you want. 


# Resources
- [MDN on forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
- [w3Schools on forEach](https://www.w3schools.com/jsref/jsref_foreach.asp)
- [JavaScript — The difference between ForEach, and For…In](https://codeburst.io/javascript-the-difference-between-foreach-and-for-in-992db038e4c2)
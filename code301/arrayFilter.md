# Lecture Notes
Array.Filter


# ✍️ Notes

1. What is the definition of the filter method?
* The filter() method creates a new array with all the elements that pass the test implemented by the provided function.

2. What data type can you call a filter on?
* An array

3. What does the syntax / pseudocode look like for the filter method?
* array.filter(callback(currentValue, index, arr), thisValue)

4. What other methods do we know of that have the same syntax?
* array.map or forEach

5. Which parameters are required for the filter method?
* callback
-element

6. What is the output of the filter method?
* a new array with the elements that pass the test. If no elements pass the test, an empty array will be returned. 

7. How does filter decide which array elements to return?
* If the element is true it is returned. If the element is false it is not returned. 

8. Is the original array mutated in the filter process?
* No the original array is never mutated.

9. Does the filter method give us back a new array?
* You always get back a new array. 

10. What does filter return if no array elements pass the test?
* An empty array will be returned. 


# Resources
- [MDN on Array.Filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
- [w3Schools on Array.Filter](https://www.w3schools.com/jsref/jsref_filter.asp)
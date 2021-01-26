My Notes
# JavaScript
Primitive Types in JS
- Number
- String 
- Boolean 
- Null 
- Undefined 

Numbers
- Js has one number type
- Positive Numbers 
- Negative Numbers
- Whole numbers (integers)
- Decimal numbers (floats)

------------------------------------
Booleans 
another primitive type
- True or False values

Variables can change types

----------------------------------
Strings represent text and must be wrapped in quotes
- Strings are indexed, each character has a corresponding index
( positional number)

example 
let animal = "Dumbo Octopus"
animal[0]  
//result  D

Methods are built in actions we can perform with individial strings

They helps us do things like
- Searching within a string
- replacing part of a string
- changing the casing of string

.length is a property not a method

thing.method()

example 
let msg = "fbgm"
msg.toUpperCase() //returns "FBGM"

- .trim() -- trims leading and trailing spaces
- .indexOf("") gives us string index
- .slice(beginIndex, endIndex) is going to extract or slice a portion of a string and returns it as a new string.
takes in (beginindex, endindex )is optional

- .replace("","")
first argument is what you want to repleace
second argument is what you want to replace with
- .repeat() argument it takes how many times you want string to repeat

Null & Undefined
- Null: Intentrional absence of any value , must he assigned 
- Undefined: 
Variables that do not have an assigned value are undefined


Math Object
contains properties and methods for mathematical constants and functions 

- Math.PI // 3.1415....

- Math.round(4.9) // 5 rounds

- Math.abs(-456)//456 absolute value

- Math.pow(2,5) //32 raises 2 to the 5th power

- Math.floor(3.999) //3 removes decimal

console.warn("")// prints yellow
console.error("") prints red
alert("") // pop up
prompt("") // pop up allows user to user input
parseInt() // converts string to int

.push method allows you to push item to end of array for example 
a = [ 'b', 'c', 'd']
a.push('x')

a = [ 'b', 'c', 'd', 'x']

# Array Methods
- Push - add to an end
- Pop - remove from end
- Shift - remove from start 
- Unshift - add to start
- concat - merge arrays
- includes - look for a value
- indexOf - just like string.indexOf
- join - creates a string from an array
- reverse - reverses an array 
- slice - copies a portion on an array 
- splice - removes/replaces elements 
- sort - sorts array 

# Goals for this section (subset of array methods)
- Use the new arrow function syntax
- understand and use these methods
    - forEach
    - map
    - filter 
    - find 
    - reduce 
    - some 
    - every 

# ForEach 
 - accepts a callback function. calls the function once per element in the array
// const numbers = [1,2,3,4,5,6]
// numbers.foEach(function (el) {
    console.log(el)
})
prints 
1
2
3
....

# map
- creates a new array with the results of calling a callback on every element in the array

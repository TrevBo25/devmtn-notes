########################
### String Reference ###
########################

## Properties
    .length — Returns or references the length of given string or array. 

## Methods — red means method is also applicable to arrays & numbers
    indexOf() — Returns the index (position) of a given item within a string
    charAt() — The opposite of indexOf; Returns the character at the specified index 
    concat() — Joins two or more strings and returns the new joined string
    endsWith() — Checks whether a string ends with specified string/characters
    charCodeAt() — Returns the Unicode of the character at the specified index 
    fromCharCode() — Converts Unicode values to characters 
    includes() — Checks whether a string contains specified string/characters 
    lastIndexOf() — Returns the position of the last found occurrence of a specified value within a string 
    localeCompare() — Compares two strings in the current locale
    match() — Searches a string for a match against a regular expression, returns the matches
    repeat() — Returns a new string with a specified number of copies of an existing string
    replace() — Searches a string for a specified value, or expression, and returns a new string where the specified values are replaced
    search() — Searches a string for a specified value, or expression, and returns the position of the match
    slice() — Extracts a part of a string and returns a new string
    split() — Splits a string into an array of substrings
    startsWith() — Checks whether a string begins with specified characters 
    substr() — Extracts the characters from a string, beginning at a specified start position, and through  the specified number of characters 
    substring() — xx
    toLocaleLowerCase() — xx
    toLowerCase() — xx
    toLocaleUpperCase() — xx
    toUpperCase() — xx
    toString() — Converts an array to a string, and returns the result
    trim() — xx
    valueOf() — Returns the primitive value of an array

########################
### Number Reference ###
########################

## Properties
    constructor
    MAX_VALUE
    MIN_VALUE
    NEGATIVE_INFINITY
    NaN - N.ot A. N.umber
    POSITIVE_INFITITY
    prototype
## Methods
    isFinite() — Checks whether number is finite 
    isInteger() — Checks whether number is an integer 
    isNaN() — Checks whether number is not a number
    isSafeInteger() — Checks whether number is a safe integer 
    toExponential() — Converts number into an exponential notation
    toFixed() — Formats a number with x digits after the decimal 
    toPrecision() — Formats a number to x length
    toString() — Converts number to a string 
    valueOf() — Checks whether number is primitive 

#######################
### Array Reference ###
#######################

## Methods
    indexOf() — Returns the index (position) of a given item within a string
    charAt() — The opposite of indexOf; Returns the character at the specified index 
    concat() — Joins two or more arrays and returns a copy of the joined arrays
    endsWith() — Checks whether a string ends with specified string/characters
    slice() — Extracts a part of a string and returns a new string
    replace() — Searches a string for a specified value, or expression, and returns a new string where the specified values are replaced
    includes() — Checks whether a string contains specified string/characters 
    filter() — Creates a new array with every element in an array that pass a test
    find() — Returns the value of the first element in an array that pass a test
    fill() — Fill the elements in an array with a static value
    every() — Checks if every element in an array pass a test
    findIndex() — Returns the index of the first element in an array that pass a test 
    forEach() — Calls a function for each array element 
    isArray() — Checks whether an object is an array
    join() — Joins all elements of an array into a string
    lastIndexOf() — Returns the position of the last found occurrence of a specified value within a string 
    map() — Creates a new array with the result of calling a function for each array element
    pop() — Takes the item off the end of an array and returns it to you
    push() — The opposite of pop; Adds an item to the end of an array
    reduce() — Reduce the values of an array to a single value (going left-to-right)
    reduceRight() — Reduce the values of an array to a single value (going right-to-left)
    reverse() — Reverses the order of the elements in an array
    shift() — Takes the item off the front of an array and returns it to you
    slice() — The opposite of splice; selects parts of an array, and returns the new array
    some() — Checks if any of the elements in an array pass a test
    sort() — Sorts the elements of an array
    splice() — Adds/Removes elements from an array
    toString() — Converts an array to a string, and returns the result
    unshift() — The opposite of shift; Adds new elements to the beginning of an array, and returns the new length
    valueOf() — Returns the primitive value of an array


## Methods Explained
1: Converting Arrays to Strings
    + toString()

2: Popping and Pushing
    + pop()
    + push()

3: Shifting Elements
    + shift()
    + unshift()

4: Changing Elements
    - Array elements are accessed using their index number
    + indexOf()
    + charAt()
        
5: Deleting Elements 
    + delete()
        
6: Splicing an Array
    + Using splice() to add an element(s)
    + Using splice() to remove an element(s)
        
7: Merging Arrays
    + concat()
        - Can be used on multiple strings
        - As seen in: 
            var myGirls = [“Cecilie”, “Kathy”];
            var myBoys = [“Marco”, “Ryan”, “Paul”];
            var myDogs = [“Spot”, “Otis”];
            var allMyChildren = myGirls.concat(myBoys, myDogs); // returns [“Cecilie”, “Kathy”, “Marco”, “Ryan”, “Paul”, “Spot”, “Otis”]

8: Slicing an Array
    + slice()

9: Automatic toString()
    - JavaScript automatically converts an array to a comma separated string when a primitive value is expected
    - You can also use indexOf() to return a primitive value; for example, in a string

10: Finding Max and Min Values in an Array
     - There are no built-in functions for this process

11: Sorting Arrays
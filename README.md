# Notes


* ES1-Ecma script one
* Attribute example- id,src,style
* advantage of using external javascript file- file is saved as cached in browser when it loads first time.It speedup page load 

## Javascript Output

* innerHtml
* document.write()-used for testing purpose
* window.alert()
* console.log()

## Javascript Statement

* javascript code block-code under curly braces is called code block
* javascript case sensitive

## keywords

* let keywords introduced in 2015 es5
* let can be declared 1 time 
* let & const introduced block
* VAR inside a block is global,we cannot declare var as a block element other hand we can declare let as a block element
* redeclare with let in another block is allowed
* let & var both hoisted at the top but the diffrence between both is var automatically declared as undefined but let stay in temporal dead zone.Thats why before declaring we can assign something to a var but not in let.

## operator

* typeof is a operator

## Data types

* when we add a number and string ,javascript will print the result as a string 
* javascript evaluates expression from left to right
* Example - let a= 5 + 6 + "string";
* Ans: 11string
* Javascript types are dynamic .Example - let a=5; a="string";
* undefined is datatype


## Events

* the function inside event is called event handler function

## String

* string addition - > "Hello" + "World"
* String can defined as object by declaring with 'New' keyword
*  == check the value is same or not
* === check the value and type is same or not
* object cant be compared like == or ===

## string methods

* s.slice(startindex,endindex);
* if the index perameter is negative it counts from end of the string 
* s.substr(startindex,length)
* s.replace(string1,string2)
* it replace only first match and return a new string
* s.toUpperCase()
* s.toLowercase()
* s.concat(" ",string2)
* s.trim() removes all whitespace
* s.split(" ") make an array of words
* s.split("") make an array of characters
* all string method is immutable,string can not be changed ,only replaced.

## String search

* s.indexof("string")
* s.lastIndexof("string")
* returns -1 if not found
* s.search()
* s.includes()

## template leterale

* `string ${something } string`


## number

* javascript has only one type of number which is 64 bit floating number
* integers are accurate to 15 digits
* string + number = stringcotanation
* plus has separate rules
* multiolication and division can be done in string
* example "100"/"10"=10
* nan - not a number
* nan is a number
* typeof Nan IS A NUMBER

## numbermethod

* toString() returns a number as a string 

## array

* array.toString() convert array to string
* array.join(" * ") convert to string with custmize space
* array.pop() return the value of arrays last element
* array.push("string") 
* array.push() returns new length of array
* array.shift() remove first element and return first element
* array.unshift("5") add a element in the first index
* array.unshift returns the  length of new array
* using array.delete make a hole in array.use shift or pop instead
* array.splice(2,0,"string1","string2")
* first perameter defines which position to splice
* second perameter defines how many element to delete
* rest permeter is the element to add in array
* array.concate(arra1) merge two array
* array.slice(1,3) returns a new array (kup)

## array sort

* sort compare string value
* for numaric value we need to make compare function

## javascript LOOPS

* for loop
* for in loop
* for of loop
* while  loop

## itarabels

* javascript objects are not iterable

## javascript regular expression

* search(), replace()
* /i case insensetive
* /g global
* /m multiline
* [a-z,1-9] find any character between the bracket
* [x|y] find any alternative
* metacharacter /d for digit search, \s find a white space , \b find the begining of the word
* n? zero or one

## errors

* try,catch,throw,finally





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


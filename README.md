# JavaScript

Math with JavaScript

-order pf precedence 
() * / + -  comparision operators logical operators

- calculating the cents first and rounding to dollars /100
rounding the numbers to nearest integers Math.round()
Math.round(cents calulation) /100 -> avoid floating errors

String 
typeof 2
typeof 'Hello'
'hello' + 3 -> 'hello3'

3 types of strings
''  ""   ``

`` -> template string
features: 

1. Interpolation - lets to insert the value directly in the string 
`Items(${1+1}): $${(2095+799)/100}`

2. Multiline strings 
`some
text`  
-> 'some\ntext'


Naming conventions
- camelCase
- PascalCase
- kebab-case (doesn't work in javascript however we can use in html and css)
- snake_case

logical operators 
and Or Not


Truthy and Falsy 

Falsy are : 0 '' Nan false undefined Null apart from this all value are truthy

functions:

return: returns the value out of the function
the functions ends after the return statement

so apart from using local and gloabl variables we can just return the value

parameter : puts the value into the function

objects:

dot notation and bracket notation 
bracket notation allowes us to take the property that dot notation doesn't allow us to do.

we use dot notation by default expect for the cases where we need bracket notation.

built in objects
provided by language example:console, math 
json
localStorage

Json Built in Object

- helps us work with json
javascript object notation
it is a syntax similar to javascript but has less features
everything is in double quotes in json and json doesn't support functions 
we use json when we send data between two computers, javascript features is limited to javascript only where as json is universal. 

Built In json object:
helps us convert javascript object to json and vice versa

More about Objects:
Null : null is a falsy value similar to undefined that something doesn't have value.
null: when we want something to be empty intentionally

 objects can have properties and methods other value also have properties and methods 
 hello.length
 hello.toUpperCase()
 hello is just a string and yet it has property and object ?
 its because of the javascript feature autoboxing which automatically wraps the string into special object 
 Also works with boolean and numbers but cannot work with Null and undefined.

 - Objects are references

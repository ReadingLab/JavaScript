# JavaScript: The Definitive Guide, 6th Edition

-----

把 《JavaScript: The Definitive Guide, 6th Edition》 读薄

## Chapter 1 Introduction to JavaScript

JavaScript to specify the **behavior** of web pages.

version calls:

- `ECMAScript 5`
- `version 1.5` : Mozilla's version
- `V8` : Google "engines".

> When learning a new programming language, it’s important to try the **examples** in the book, and then **modify** them and try them again to test your understanding of the language.

-----

`console.log()` : display text on the console.

`alert()` : displays text in a modal dialog box.

-----

**Type**

```js
var x;
x = 1;      // Numbers
x = 0.01;   // Just one Number type for integers and reals
x = "hello, world"; // string
x = 'JavaScript';   // string
x = true;   // Boolean
x = false;  // Boolean
x = null;   // no value
x = undefined;  // null

var book = {
    topic: "JavaScript",
    fat: ture
};
book.topic  // => "JavaScript"
bool["fat"] // => true
book.author = "pezy";
book.contents = {}; // {} is an empty object.

var primes = [2, 3, 5, 7];  // array
primes[0]   // => 2
primes.length   // => 4
primes[primes.length-1] // => 7
primes[4] = 9;  // create
primes[4] = 11; // alter
var empty = []; // [] is an empty array
empty.length    // => 0

var points = [
    {x:0, y:0},
    {x:1, y:1}
]
var data = {
    trial1: [[1,2], [3,4]],
    trial2: [[2,3], [4,5]]Â
}
```

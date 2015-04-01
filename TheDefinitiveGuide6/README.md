# JavaScript: The Definitive Guide, 6th Edition

-----

把 《JavaScript: The Definitive Guide, 6th Edition》 读薄

## Chapter 1 Introduction to JavaScript

### Core

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

**Expressions**

```js
"3" + "2" // => "32"
count++;
count += 2;
```

**class**

```js
function Point(x,y) {
    this.x = x;
    this.y = y;
}

var p = new Point(1, 1);

// Define methods for Point objects by assigning them to
// object associated with the constructor function.

Point.prototype.r = function() {
    return Math.sqrt(
        this.x * this.x +
        this.y * this.y
    );
}

p.r() // => 1.414...
```

### Client-Side

see [calculator](http://readinglab.github.io/JavaScript/calcuator)

# Part I Core JavaScript
## Chapter 2 Lexical Structure

- Unicode character
- a number of global variables and functions
```js
arguments   encodeURL           Infinity    Number          RegExp
Array       encodeURIComponent  isFinite    Object          String
Boolean     Error               isNaN       parseFloat      SyntaxError
Date        eval                JSON        parseInt        TypeError
decodeURI   EvalError           Math        RangeError      undefined
decodeURIComponent  Function    NaN         ReferenceError  URIError
```
- notify the optional semicolons.
```js
x
++
y
// same as following:
x; ++y;
// not this:
x++; y;
```

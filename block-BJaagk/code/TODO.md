1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let percentage = function (marks, total) {
  return (marks * 100) / total;

let percentage = (marks, total) => {
  return (marks * 100) / total;
}

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
// expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
// expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
// expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;
// expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

```js
An expression is something that gives a value as a result.
A function is an object. An object is a value.
Values can be stored in variables.

function add() {
}

let obj = {};

let add = function(){};

```

4. Why is a function call an expression in JavaScript?

```js
function add(a,b) {
  return a + b;
}

// with return function

function addAgain(a,b) {

}

// without return function

add(12,23); // we get an output which is 35
addAgain(12, 23); // no return statement so it will return undefined.

//undefines and 35 are both values.

// A function call always returns a value (whether it's undefined or a number) and this is why it is an expression.
```

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // VALID 5
five = add; // VALID
five = five(10, 11); // VALID 21
five = function () {
  return 'Hello';
}; // VALID
```

6. What is the difference between function definition and function call? Explain with an example.

```js

FUNCTION DEFINITION:

function house(windows, doors) {
  return `The house has ${windows} windows and ${doors} doors.`
}

FUNCTION CALL:

house();
```

7. What is the similarities between function definition and function call?

```js
Function definition is an expression (function definition is an object which returns a value)
Function call is an expression (function call returns a value - undefined or other - depending on if it has a return statement or not)
```


8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // VALID Because a function is an object
```

9. What is higher order function explain with an example.

```js
A higher order function is when you pass a function inside a function either as an argument or as a returned result.

It either:

~ accepts a function definition or 
~ returns a function definition

let sum(cb) {
cb();
}

// Or

function add() {
  function main(){};
  return main;
}

```

10. Explain what is callback function. Why you can pass a function inside a function?

```js
A callback function is when a function is passed inside another function as an argument.

Because a function is an expression in js, we can pass a function inside another function. 

(Arguments are expressions)
```

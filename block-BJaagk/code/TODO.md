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

```
Because a function is an object.

let house = (windows, doors) => `The house has ${windows} windows and ${doors} doors.`
}
```

4. Why is a function call an expression in JavaScript?



5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // VALID
five = add; // INVALID
five = five(10, 11); // VALID
five = function () {
  return 'Hello';
}; // VALID
```

6. What is the difference between function definition and function call? Explain with an example.

```

FUNCTION DEFINITION:

function house(windows, doors) {
  return `The house has ${windows} windows and ${doors} doors.`
}

FUNCTION CALL:

house();

7. What is the similarities between function definition and function call?



8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // INVALID
```

9. What is higher order function explain with an example.

A higher order function is when you pass a function inside a function either as an argument or as a returned result.

houses.map((a,b) => a + b));

10. Explain what is callback function. Why you can pass a function inside a function?

A callback function is when a function is passed inside another function as an argument.

function example(a) {
  return a + 2;
}

function add(num1, num2, cb) {
  let sum = num1 + num2;
  cb(sum);
}

add(example);

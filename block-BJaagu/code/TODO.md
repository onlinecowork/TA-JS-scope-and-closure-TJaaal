Find the output of the code snippets below:

```js
console.log(numA + numB); // 51
var numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
console.log(numA + numB); // 51
let numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); // Uncaught SyntaxError: Identifier 'numA' has already been declared
```

Find the output of the code snippets below:

```js
console.log(sayHello()); // Hello
function sayHello() {
  console.log("Hey");
}
function sayHello() {
  console.log("Hello");
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // Tyrion
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
sayHello(); // Tyrion
let username = "Tyrion";
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // Uncaught SyntaxError: Identifier 'sayHello' has already been declared
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // Uncaught SyntaxError: Identifier 'sayHello' has already been declared
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // Uncaught SyntaxError: Identifier 'sayHello' has already been declared
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello(); // Uncaught SyntaxError: Identifier 'sayHello' has already been declared
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  var username = "John";
};
sayHello(); // Uncaught SyntaxError: Identifier 'sayHello' has already been declared
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); // Uncaught SyntaxError: Identifier 'sayHello' has already been declared
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); // Uncaught SyntaxError: Identifier 'sayHello' has already been declared
```
1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
```

const percentage=(marks,total) => {
return (marks \* 100) / total;
}

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
   because function is object

   const add = (a,b) => {
     return a+b;
   }

4. Why is a function call an expression in JavaScript?
   functions are values in js as they can be assigned, copied.



5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer valid
five = add; // Answer valid
five = five(10, 11); // Answer valid
five = function () {
  return 'Hello';
}; // Answer valid
```

6. What is the difference between function definition and function call? Explain with an example.
   function definitions contains series of statements to be executed and function call executes them

7. What is the similarities between function definition and function call?
   No Similarity

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; //  valid
because hello is object
```

9. What is higher order function explain with an example.
   higher order function is a function which takes function as argument or returns function

Ex:

const High = () => {
console.log("high")
}

const higherOrderFunction(High){
High();
}

10. Explain what is callback function. Why you can pass a function inside a function?

callback function is a function that is passed into another function as an argument. This function can then be invoked during the execution of that higher order function

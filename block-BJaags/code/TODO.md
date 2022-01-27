To create the execution context diagram consider the following:

- Global and Function Execution Context
- Different Phases Of Execution Context
- Var let and const

Create the execution context diagram of the following code line by line.

```js
let num = 21;
function square(num) {
  return num * num;
}
let hundred = square(10);
console.log(hundred);
```
let num
function square(num) {
  return num * num;
}
let hundred

num=21
hundred=100
100


Create the execution context diagram of the following code line by line.

```js
var num = 21;
function addFive(n) {
  return n + 5;
}
var five = addFive(0);
var ten = addFive(5);
console.log(five, ten);
```
var num = undefined
function addFive(n) {
  return n + 5;
}
var five = undefined;
var ten = undefined;

num=21;
five=5;
ten=10;

5,10


Create the execution context diagram of the following code line by line.

```js
let marks = [34, 45, 56, 76];
function multiplyArrayByN(arr, n) {
  let finalArr = [];
  for (let elm of arr) {
    finalArr.push(elm * 2);
  }
  return finalArr;
}

let numbers = multiplyArrayByN(marks);
```

let marks
function multiplyArrayByN(arr, n) {
  let finalArr = [];
  for (let elm of arr) {
    finalArr.push(elm * 2);
  }
  return finalArr;
}
let numbers

marks = [34, 45, 56, 76];
numbers = [68,90,112,152];


Create the execution context diagram of the following code line by line.

```js
counter();
function counter(){
  let count = 0;
  funciton increment(){
    return count++;
  }
  return increment()
}
```
GEC
counter

fec
let count
funciton increment(){
  return count++;
}

count=0;
1

increment fec
1

Create the execution context diagram of the following code line by line.

```js
counter();
let counter = function () {
  let count = 0;
  function increment() {
    return count++;
  }
  return increment();
};
```

gec
let counter
counter is not defined

Answers

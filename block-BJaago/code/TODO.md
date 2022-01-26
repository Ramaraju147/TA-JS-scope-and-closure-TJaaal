Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.

- Take in account the different phases of execution, different execution contexts

1.

```js
var firstName = "Arya";
var lastName = "Stark";

function getFullName(first, last) {
  return `${first} ${last}`;
}

function sayHelloToUser(name) {
  return `Hello ${name}, How are you doing?`;
}

var fullName = getFullName(firstName, lastName); //Arya Stark
var jon = getFullName("John", "Snow"); // John Snow

console.log(fullName); //Arya Stark

var userMessage = sayHelloToUser("Bran"); // Hello Bran, How are you doing?
```

<!-- Put your image below -->

![](./img/image-name.jpg)

2.

```js
function sayHi() {
  var name = "Lydia";
  var age = 21;
  console.log(name);
  console.log(age);
}

sayHi();
// Lydia
// 21
```

<!-- Put your image below -->

![](./img/image-name.jpg)

3.

```js
function sayHi() {
  console.log(name);
  console.log(age);
  var name = "Lydia";
  var age = 21;
}

sayHi();
// undefined 
// undefined
```

<!-- Put your image below -->

![](./img/image-name.jpg)

4.

```js
console.log(arr); // output undefined
console.log(username); // output undefined
var usename = "Sam";
var arr = [1, 2, 3, 4, 5, 6];
test;
function double(num) {
  return num * 2;
}
```
